# AlumierMD Take-Home Task

## Task Overview
Create a Liquid snippet to display a custom product badge ("On Sale") on product pages when items are discounted, including support for products with multiple variants where only some variants are on sale.

## Demo Store Access
- Store URL: https://alumiermd-tht.myshopify.com/
- Password: bustot

## Test Products
- Discounted Price Example: [The 3P Fulfilled Snowboard](https://alumiermd-tht.myshopify.com/products/the-3p-fulfilled-snowboard?variant=50337148436810)
- Compare at Price Example: [The Multi Managed Snowboard](https://alumiermd-tht.myshopify.com/products/the-multi-managed-snowboard?variant=50335187763530)

## Implementation Details

### Component Overview
Created `sales-badge.liquid` to handle two main pricing scenarios:
1. Compare at price
2. Discounted price

### Key Features
- Modular and reusable component design
- Dedicated Theme Settings section for store administrators
- Basic accessibility support (aria-label and role attributes)
- Variant-specific sale detection

### Technical Implementation
- **Compare at Price Scenario**: Implemented core functionality with added theme setting controls
- **Discounted Price Scenario**: Matches variant IDs between product and cart object to determine sale status
- **Version Control**: Used commit strategy over rebase to document development process
- **Deployment**: GitHub integration for streamlined deployment

### Future Improvements
1. UI Enhancements
  - Add border radius controls
  - Extend sales badge to Product List Page 
  - Add sales badge to cart interface

2. Code Quality
  - Implement Theme Check
  - Add code formatting standards

3. Accessibility & Internationalization
  - Expand accessibility features
  - Add multi-language support
