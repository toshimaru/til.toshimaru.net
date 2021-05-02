# frozen_string_literal: true

require 'date'

task :til do
  today = Date.today.to_s
  filename = "_posts/#{today}-til.md"
  File.write(filename, <<~YAML)
    ---
    title: #{today}
    ---
  YAML

  puts "#{filename} has been created!"
end

task :noindex do
  File.write("robots.txt", <<~TXT)
    TODO: noindex
  TXT
end
