# README

workout
belongs_to :user
- length
- description
- user_id


user
has_many :workouts
has_secure_password
- email
- password_digest

signup
