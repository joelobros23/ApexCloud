# Project Plan: ApexCloud

**Description:** A simple and scalable web hosting platform for managing domains and user accounts, built with Rails, Tailwind CSS, and Devise.


## Development Goals

- [ ] Configure the tailwindcss-rails gem: `bundle install` and `rails tailwindcss:install`.
- [ ] Update application.tailwind.css to include necessary Tailwind directives and custom styles.
- [ ] Implement domain validation rules in the Domain model (e.g., unique name per user, allowed plans).
- [ ] Customize the Domain scaffold views using Tailwind CSS for improved aesthetics and usability (index.html.erb, show.html.erb, _form.html.erb).
- [ ] Modify the DomainsController to associate each new domain with the currently logged-in user using `current_user.domains.build`. Ensure users can only manage their own domains.
- [ ] Implement authorization using CanCanCan or Pundit to further restrict access to domain management based on user roles (e.g., admin, user).
- [ ] Create a dashboard or user profile page to display a list of the user's domains.
- [ ] Add basic domain status indicators (e.g., active, pending, suspended) and management options (e.g., renew, cancel).
- [ ] Implement a basic pricing plan system (e.g., Free, Basic, Premium) and associate them with the Domain model.
- [ ] Configure Devise to allow users to register, login, and manage their accounts effectively. Customize devise views with tailwind CSS.
- [ ] Implement a system for users to update their profile (username, email, password).
- [ ] Add seed data for default plans.
- [ ] Add a role attribute to the User model (default to 'user') to implement some basic authorization.
