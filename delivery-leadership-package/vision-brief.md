# Evergreen Quote: Vision Brief

> Copy this file into `delivery-leadership-package/vision-brief.md` in your repo and fill it in. Target length: 1 page (~300 words). Write for a Liberty Mutual VP who has 90 seconds.

## Product
**Name:** Evergreen Insurance Quote (Phase 2 React rebuild)
**Delivery week:** 2
**Delivery Lead:** Yamini Dumpala
**Engineering team (represented by):** _link to your Evergreen Quote project repo_
**GitHub Project board:** _link_

## Who is the customer?
The customer is a first-time insurance shopper, likely a new renter or homeowner, who has been told they "need insurance." They are looking for a fast, no-commitment price estimate on their phone. This customer segment is not loyal to any specific carrier and will quickly abandon any website that asks for extensive personal information before showing a price. Their current alternative is a competitor's site, which may have a more tedious and less transparent quoting process.

## What pain does Evergreen Quote remove?
Evergreen Quote removes the friction and uncertainty of getting an insurance estimate. In the customer's words, they no longer have to "fill out a long form and press a button just to see a number." Phase 1 required a button press, but the Phase 2 rebuild provides a live premium estimate that updates instantly as they type. This immediate feedback gives the customer a sense of control and transparency, preventing them from getting frustrated and "bouncing to a competitor."

## What does "good" look like at end of the week?
_3–5 bullets. Each one should be observable: something a stakeholder could check on Thursday afternoon._
The application runs locally without errors after a fresh install 
The premium estimate updates live on the screen as a user changes the coverage type, age, or amount.
The "Recent quotes" list shows a loading state, successfully loads data from the feed, and a new quote can be saved to the top of the list.
- The project's code is type-safe and can be successfully built for production with no errors
- All work is merged into the main branch through a pull request that has been reviewed and has a green continuous integration (CI) build.

## What are we explicitly NOT doing this week?
_3–5 bullets. This is where you protect your team from scope creep._
Building a real rate engine with actuarial pricing; the current model is a placeholder.
Implementing user accounts, saving quotes to a database, or capturing email addresses.
Adding any payment, checkout, or policy purchasing functionality.
Creating a back-end service; a static JSON file will stand in for the quotes API.
Adding routing, test suites, or deploying the application to a live server.



## How will we know if it worked?
_2–3 measures. Numeric if possible._

- We can measure the number of believable premium estimates generated for each coverage type (auto, home, and life).
The "Recent quotes" section loads data correctly and that saved quotes appear at the top of the list.
Success is a green build in the CI pipeline, indicating that the code is free of type errors and ready for a hypothetical deployment.




- 
