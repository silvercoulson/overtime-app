# Overtime App

## Key requirement: company needs documentation that salaried employees did or did not get overtime each week

## Models
- x Post -> date:date rationale:text
- x User -> Devise
- x AdminUser -> STI

## Features:
- Approval Workflow
- SMS Sending -> link to approval or overtime input
- Administrate admin dashboard
- Email summary to managers for approval
- Needs to be documented if employee did not log overtime

## UI:
- Bootstrap -> formatting
- Icons from Font Awesome
- Update the styles for forms

## Refactor TODOS:
- Add full_name method for users
- Refactor user association integration test in post_spec