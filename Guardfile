# group :sass do
#    guard "sass",
#        :all_on_start => true,
#        :output => "main/webapp/static/css/",
#        :input => "sass",
#        :compass => {
#            :images_dir => "",
#            :images_path => "",
#            :http_images_path => "",
#            :http_images_dir => "",
#            :http_fonts_path => "",
#            :http_fonts_dir => "",
#            :load_paths => "psdweb"
#    }
# end

group :compass do
   guard "compass",
       :sass_config => {
           :all_on_start => true
       }
end