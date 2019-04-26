# [Backend Senior Java Developer](https://gourban-mobility.com/career.html#job-292434)

This is the coding challenge for the job posting from [Backend Senior Java Developer](https://gourban-mobility.com/career.html#job-292434) on the [goUrban Career Site](https://gourban-mobility.com/career.html).

## Goal

The goal of this challenge is to write a small client for the [Stripe](https://stripe.com/)-Platform.

We sent you an Stripe Test ApiKey by email. If not pls ask for it.

## Task

Write a small *console* client for Stripe for the following scenario:

1. Ask user for email.
2. User enters email.
3. Create customer at stripe with the entered email address.
4. Create a credit card source in stripe with token `tok_at` and type `card` and attach it as default source to the created customer.
5. Ask user for the amount of the charge in Euro.
6. Create a charge for the requested amount.
7. Ask the user if he wants to chapture the charge or refund it.
8. Charge or refund the charge.

If an exception/error occurs the charge should be refunded. Implement exception handling when calling Stripe resources as you would do in a production environment. Reads/Writes from/to console can be considered to work as they should but user input should be validated.


## Resources

- [Stripe Testing](https://stripe.com/docs/testing)
- [Stripe Java SDK](https://github.com/stripe/stripe-java)
- [Stripe Documentation](https://stripe.com/docs/development)


## Prerequisites

- Use Java 8 as the programming language.
- Use the packaging/build tool of your choice.
- Write the task either as a junit test or as a console programm (ie. _public static void main_)
- Use the Spring Boot framework whenever usefull.

## Constraints

- Should be runable on Windows/Linux/OS X platforms whenever the appropriate build tools are installed.