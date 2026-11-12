# Nations Clothing

Website for Nations Clothing, a unisex fashion house in Lagos, Nigeria: https://nationsclothing.org

Runway of looks, new arrivals, women's collection, catalogue and cart. Customers check out with their
delivery details, get an order number, and send the order to the shop on WhatsApp.

## Admin

The team manages the shop at https://nationsclothing.org/admin/ (not linked from the site).

- **Orders:** every checkout, with the customer's details, a status (new, confirmed, paid, shipped,
  delivered, cancelled) and private team notes. One tap to WhatsApp or call the customer.
- **Customers:** everyone who has ordered, grouped by phone number, with order count and amount spent.
  Orders and customers download as spreadsheets.
- **Products:** add pieces, change prices, sizes, colours and pictures; choose whether each one shows in
  the catalogue, the Women section, New arrivals or the runway; mark pieces sold out.
- **More looks:** photos for the "More looks" section.
- **Site info:** WhatsApp number, Instagram, welcome text, Women section text, footer and order policy.
- **Team:** owners invite people by link, change roles and make password reset links.
- **Recently deleted:** anything deleted can be restored for 30 days.

Content lives in Supabase (project `nations-clothing`). The site keeps a built-in copy of the starting
content, so it still works if the database cannot be reached. Prices are always re-checked by the
database when an order is placed.
