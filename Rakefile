namespace :book do
  desc 'prepare build'
  task :prebuild do
    Dir.mkdir 'images' unless Dir.exists? 'images'
    Dir.glob("book/*/images/*").each do |image|
      FileUtils.copy(image, "images/" + File.basename(image))
    end
  end

  desc 'build basic book formats'
  task :build => :prebuild do
    puts "Converting to HTML..."
    `bundle exec asciidoctor iis-handbook.asc`
    puts " -- HTML output at iis-handbook.html"

    puts "Converting to EPub..."
    `bundle exec asciidoctor-epub3 iis-handbook.asc`
    puts " -- Epub output at iis-handbook.epub"

    puts "Converting to Mobi (kf8)..."
    `bundle exec asciidoctor-epub3 -a ebook-format=kf8 iis-handbook.asc`
    puts " -- Mobi output at iis-handbook.mobi"

    puts "Converting to PDF... (this one takes a while)"
    `bundle exec asciidoctor-pdf iis-handbook.asc 2>/dev/null`
    puts " -- PDF  output at iis-handbook.pdf"
  end
end

task :default => "book:build"
