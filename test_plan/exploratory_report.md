# Exploratory Testing Report – Buggy Cars Rating

**Date:** YYYY-MM-DD  
**Tester:** Yuriy Chankov
**Environment:** Chrome 114, Linux Fedora 42, Wi-Fi

## Overview  
Performed manual exploratory testing to understand core features and identify immediate issues in registration, login, rating, and profile management.

## Findings

- Registration form accepts special case symbols (!@#$%^&*()_+) in the Name fileds as users' real name.
- No success message after logging in; user feedback is minimal.
- Users can submit multiple ratings for the same car without restrictions. 
- Password change form lacks confirmation message on success.
- Navigation menu is inconsistent on smaller browser widths.
- Hyperlinks on the main page are taking too long to load.

## Suggestions

- Implement password strength validation.  
- Add success and error feedback messages throughout the app.  
- Restrict multiple ratings per user/car combination.  
- Fix registration validation to prevent duplicate usernames.  
- Improve responsive behavior of navigation menu.
- Run a performance audit tool in order to identify specific bottleneck
- 
