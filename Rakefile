task :default => ["start"]

task :start do
  jekyll('serve --watch')
end

def jekyll(directives = '')
  sh 'jekyll ' + directives
end