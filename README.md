# README

# Politekh_Web_Development_Spring2022
Санкт-Петербургский Политехнический университет Петра Великого, курс Методики разработки современных WEB-приложений", Иванищев Алексей Вячеславович., 2021-2022


13.03.22
Lab 1 complete 
+ fix problem error "rake routes rake aborted!" with:

-Open your project folder
-Navigate to lib/tasks
-Create file called routes.rake
copypaste text below:

task routes: :environment do
  puts `bundle exec rails routes`
end
