task default: %w[build]

file "espiritas.dat" => "espiritas" do 
  system "fold -w 70 -s espiritas > espiritas.tmp"
  cp "espiritas.tmp", "espiritas"
  rm "espiritas.tmp"
  system "strfile espiritas"
end

desc "Compile fortunes"
task :compile => ["espiritas.dat"]

desc "Calling fortune"
task :fortune => ["espiritas.dat"]do
  system "fortune espiritas"
end

task :build => [:compile, :fortune]
