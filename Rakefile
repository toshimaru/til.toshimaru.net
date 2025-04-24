require 'date'

desc 'Create a new TIL post'
task :til do
  today = Date.today.to_s
  filename = "_posts/#{today}-til.md"
  File.write(filename, <<~YAML)
    ---
    title: #{today} TIL
    categories:
    ---
  YAML

  puts "#{filename} has been created!"
end

task default: :til
