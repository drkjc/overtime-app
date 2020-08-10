## Overtime App

## Key requirements: company needs documentation that salaried employees did or did not get overtime each week.

## Models
- x Post -> date:date rationale:text
- x User -> Devise
- x AdminUser -> STI

## Features
- Approval workflow
- SMS sending -> link to approval or overtime input
- Administrate admin dashboard
- Email summary to managers for approval
- Needs to be documented if employee did not log overtime

## UI
-  x Bootstrap -> formatting
- Icons from Font Awesome
- Update the styles for forms

## Refactor TODOS: 
- Refactor user association integration test in post_spec