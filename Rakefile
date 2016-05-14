namespace :milkiway_blog do
  desc "Create directories"
  task :create_dir do
    sh "git clone -b gh-pages https://github.com/dirtyhenry/milkiway-blog.git ~/Developer/build/milkiway-blog-gh-pages"
    sh "mkdir -p ~/Developer/build/milkiway-blog-pow"
    sh "ln -Ffvs ~/Developer/build/milkiway-blog-gh-pages ~/Developer/build/milkiway-blog-pow/public"
    sh "cd ~/.pow && ln -s ~/Developer/build/milkiway-blog-pow milkiway-blog"
  end
end
