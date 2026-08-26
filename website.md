# Example Websites

## Static Websites
- [Madness Games - Dallas, TX](https://madnessgames.com/)
  - Event calendar handled through Google Calendar Embed
  - Photos of inside to show atmosphere and inventory scale 
  - Don't have to worry about maintaining much outside of calendar and highlighted products on main page

- [The Gaming Hoard - Broken Arrow, OK](https://www.thegaminghoard.com/)
  - Shows on main page their focus and location/hours 
  - Too many pages on their overall website, but still good to look through


## Dynamic Websites
- [Bit Wyvern](https://www.bit-wyvern.com/)
  - Forced to look a bit like every other Square/Wix vendor
  - Product can be displayed dynamically including stock

- [DZ Comics - Moore, OK](https://dzcomics.com/)
  - Appears to be blend of static and dynamic
  - They push to external sources (TCG Player, Their Food/Drink menu)
  - Merch page is embeded with Shopify (whole website is built on Shopify, they pay a monthly fee for this)

# Discussion on Static vs Dynamic

## Static

### Pros
- We can control every aspect
- Small footprint, loads easily on slow connections
- No "must have stock levels pubically correct" pressure
- No forced integration with Square/Wix/Shopify
- In terms of security: attack surface is basically non-existant
- Can serve cached website if host goes down
- Cost is virtually nothing, just hosting and that's it

### Cons 
- Implementing interaction (purchasing/ordering) can be difficult unles we link out 
- Might seem "basic" to some

## Dynamic 

### Pros 
- Ability to enable online interaction when paired with a provider (Shopify, Square, Wix)
- Linking through APIs (ex: if user has subscription, give them role in Discord automatically)
- More integration across the board with other services

### Cons
- More points of failure and dissatifaction (customer expects something to work and it fails for one reason or another)
- Cost overhead (Online payment processing fees)
- More oversight required
- Less ownership and control of data and design

