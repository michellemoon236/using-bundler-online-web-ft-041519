

#     should list the hashie gem without specifying a version (FAILED - 1)
#     should list the sinatra gem with the specific version 1.4.4 (FAILED - 2)
#     should list the octokit gem specifying version 2.0 with a twiddle-wakka (FAILED - 3)
#     should list the awesome_print gem specifying a remote git repository (use github) (FAILED - 4)
#     groups
#       should contain the pry gem in the development group using a hash argumentto the gem method
# rm: cannot remove '.bundle/config': No such file or directory
#       should contain the rspec gem in the test group using block syntax (FAILED- 5)
# gem 'mail', '~> 2.6', '>= 2.6.3'

source "https://rubygems.org"
gem "hashie"
gem "sinatra", '1.4.4'
gem "octokit", '~>2.0'
gem "awesome_print", :git => "git@github\.com:awesome\-print\/awesome_print\.git"

group :development do
  gem "pry"
end

group :test do
  gem "rspec"
end 


