# A sample Guardfile
# More info at https://github.com/guard/guard#readme
guard 'rspec' do
  watch('spec/spec_helper.rb')                        { "spec" }
  watch(%r{^spec\/spec_helper\/.+\.rb})
  watch(%r{^spec/.+_spec\.rb$})
  watch(%r{^lib/(.+)\.rb$})                           { |m| "spec/lib/#{m[1]}_spec.rb" }
end