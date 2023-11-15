# User Stories

## Users

### Sign UP

- As an unregistered and unauthorized user, I want to be able to sign up for the website via a sign-up form.
  - When I'm on the `/signup` page:
    - I would like to be able to enter my email, first name, last name, zip code, and preferred password on a clearly laid out form.
    - I would like the website to log me in upon successful completion of the sign-up form.
      - So that I can seamlessly access the site's functionality
  - When I enter invalid data on the sign-up form:
    - I would like the website to inform me of the validations I failed to pass, and repopulate the form with my valid entries (except my password).
    - So that I can try again without needing to refill forms I entered valid data into.

### Log in

- As a registered and unauthorized user, I want to be able to log in to the website via a log-in form.
  - When I'm on the `/login` page:
    - I would like to be able to enter my email and password on a clearly laid out form.
    - I would like the website to log me in upon successful completion of the lob-up form.
      - So that I can seamlessly access the site's functionality
  - When I enter invalid data on the log-up form:
    - I would like the website to inform me of the validations I failed to pass, and repopulate the form with my valid entries (except my password).
      - So that I can try again without needing to refill forms I entered valid data into.

### Demo User

- As an unregistered and unauthorized user, I would like an easy to find and clear button on both the `/signup` and `/login` pages to allow me to visit the site as a guest without signing up or logging in.
  - When I'm on either the `/signup` or `/login` pages:
    - I can click on a Demo User button to log me in and allow me access as a normal user.
      - So that I can test the site's features and functionality without needing to stop and enter credentials.

### Log Out

- As a logged in user, I want to log out via an easy to find log out button on the navigation bar.
  - While on any page of the site:
    - I can log out of my account and be redirected to the landing page.
      - So that I can easily log out to keep my information secure.

## Kelp's Business

### Create new Business

- As a logged in verified business user, I want to be able to create a new business on Kelp.
  - When I'm on the `/spots/new` page:
    - I would like to be able to enter my business name, address, city, state, catagories, open hours, close hours, description, business' price range on a clearly laid out form.
      - So that my business will show up when someone is looking for it.

### Viewing all Business

- As a logged in _or_ logged out user, I want to be able to view a selection of all the business that matches the filter(business name, city, state, or zip code).

  - When I'm on the `/spots` page:
    - I can view the 6 most closely matched business.
      - So that I can choose and decide what best fit my search.

- As a logged in _or_ logged out user, I want to be able to view a specific business and its associated business' information and reviews.
  - When I'm on the `/spots/:id` page:
    - I can view the content of the specific business, as well as the associated information(hours, location, image, etc ) and reviews.
      - So that I can read and understand what sort of business this shop is running.

### Updating Business

- As a logged in business user/owner, I want to be able to edit my business by clicking an Edit button associated with the business in the user drop down menu.
  - When I'm on the `/spots/current` pages:
    - I can click "Edit" to make permanent changes to the business I have listed.
      - So that I can fix any errors I make in my business' info.

### Deleting Business

- As a logged in business user/owner, I want to be able to delete my restaurant by clicking a Delete button associated with the "manage business" anywhere that the restaurant appears.
  - When I'm on the `/spots/current` pages:
    - I can click "Delete" to permanently delete a restaurant I have listed.
      - So when a restaurant is no longer in business, the business owner can remove it.

## Kelp's Business Reviews

### Create new review

- As a logged in user, I want to be able to create a new review on a specific business on Kelp.
  - When I'm on the `/spots/:id` page:
    - I would like to be able to leave a review for that business regarding my feedback/opinions.
      - So that others may be able to see how this shop conduct their business day to day.

### Viewing all reviews on a specific business

- As a logged in _or_ logged out user, I want to be able to view a selection of all the reviews for a specific business.

  - When I'm on the `/spots/:id` page:
    - I can view up to the 8 most recent reviews.
      - So that I can decide if I want to check out this business.

### Updating Restaurant(s)

- As a logged in user that has left a review for a specific business, I want to be able to edit my review by clicking an Edit button associated with the restaurant in the review section.
  - When I'm on the `/spots/:id` pages:
    - I can click "Edit" to make permanent changes to the review I have posted.
      - So that I can fix/update any errors I make when I wrote the review.

### Deleting Restaurant(s)

- As a logged in user that has left a review for a specific business, I want to be able to delete my review by clicking a Delete button associated with the review I left in the review section.
  - When I'm on the `/spots/:id` pages:
    - I can click "Delete" button to permanently delete a review I have posted.
      - So when I feel the review is no longer relevant, I can remove it.
