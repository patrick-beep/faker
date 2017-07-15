# Faker::Commerce

```ruby
Faker::Commerce.color #=> "lavender"

# Optional arguments max=3, fixed_amount=false
Faker::Commerce.department #=> "Grocery, Health & Beauty"
Faker::Commerce.department(5) #=> "Grocery, Books, Health & Beauty"
Faker::Commerce.department(2, true) #=> "Books & Tools"

Faker::Commerce.product_name #=> "Practical Granite Shirt"

Faker::Commerce.price #=> "44.6"

# Generate a random promotion code.
# Optional argument digits = 6 for number of random digits in suffix
Faker::Commerce.promotion_code #=> "AmazingDeal829102"

Faker::Commerce.material #=> "Plastic"
```