# Hi there 👋, Welcome to QuantaJS
![Logo](https://github.com/quanta-js/quanta/blob/master/assets/quantajs_banner.png?raw=true)

Imagine a world where state management in JavaScript feels like a breeze—intuitive, lightweight, and endlessly scalable. Welcome to **QuantaJS**, the state management library that’s here to transform how you build applications. Whether you’re crafting a quick prototype or architecting a sprawling enterprise app, QuantaJS delivers a reactivity system so elegant, you’ll wonder how you ever lived without it.

<Callout type="info">
QuantaJS is in beta join us on this exciting journey and shape its future!
</Callout>

## Why QuantaJS Will Steal Your Heart

- **Freedom Unleashed**: Works anywhere JavaScript does—vanilla, React, Vue, or beyond. No framework? No problem.
- **Reactivity Redefined**: Say goodbye to clunky boilerplate. Our reactive magic tracks changes effortlessly, from simple counters to complex nested maps.
- **Scales Like a Dream**: Tiny scripts or massive systems—QuantaJS grows with you, never weighing you down.
- **Side Effects, Sorted**: Async actions feel natural, not forced. Fetch data, update state, and watch it flow.
- **API That Clicks**: Learn it in minutes, master it in hours—coding with QuantaJS feels like second nature.

QuantaJS combines simplicity with power, offering a lightweight alternative to traditional state management libraries. Whether you're building a small prototype or a large-scale app, QuantaJS adapts to your needs without unnecessary complexity.


## The Spark That Started It All

QuantaJS isn’t just another library—it’s a rebellion against bloated, overcomplicated state management. Born from a desire to simplify without sacrificing power, it’s your companion for building smarter, faster, and cleaner code. And since it’s in beta, you’re not just a user—you’re a pioneer, helping us polish this gem into something legendary.

## A Taste of the Magic

Here’s a sneak peek at what QuantaJS can do:

```javascript
import { createStore } from "quantajs";

const counter = createStore({
  state: { count: 0 },
  actions: { increment() { this.count++; } },
});

counter.increment(); // Boom! State updates, reactivity kicks in.
console.log(counter.count); // 1—simple, yet powerful.
```

## Get Started

Ready to dive in? Check out the [Installation](https://www.quantajs.com/docs/getting-started/installation) guide or explore the [Quick Start](https://www.quantajs.com/docs/getting-started/quick-start) to see QuantaJS in action!

## Support

If you like QuantaJS, give it a ⭐ on [GitHub](https://github.com/quanta-js/quanta) or contribute by submitting issues and pull requests!
