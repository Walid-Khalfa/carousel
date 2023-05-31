# Carousel React Component

This is a simple React component for a carousel that displays a set of images in a loop. The component is designed to be easy to use and customize.

## Getting Started

To use the carousel component in your React project, you can follow these steps:

1. Clone the repository or download the source code.

2. Install the dependencies by running `npm install` or `yarn install`.

3. Import the Carousel component in your React component:

```javascript
import Carousel from './Carousel';
```

4. Use the Carousel component in your JSX code, passing the images as an array of strings and any other props you want to customize:

```jsx
<Carousel
  images={[
    'https://example.com/image1.jpg',
    'https://example.com/image2.jpg',
    'https://example.com/image3.jpg',
  ]}
  interval={3000}
  speed={1000}
/>
```

5. Customize the component by passing additional props:

- `interval`: The time in milliseconds between each slide transition. Default is 5000ms.
- `speed`: The time in milliseconds for each slide transition. Default is 1000ms.
- `autoPlay`: Whether the carousel should play automatically. Default is `true`.
- `showNavButtons`: Whether to show the navigation buttons. Default is `true`.
- `showDots`: Whether to show the pagination dots. Default is `true`.
- `dotColor`: The color of the pagination dots. Default is `#fff`.
- `dotActiveColor`: The color of the active pagination dot. Default is `#007bff`.
- `navButtonColor`: The color of the navigation buttons. Default is `#fff`.
- `navButtonHoverColor`: The color of the navigation buttons on hover. Default is `rgba(255, 255, 255, 0.5)`.

## Contributing

If you want to contribute to the project, you can fork the repository and create a pull request with your changes. Before submitting a pull request, make sure to run the tests and lint the code:

```bash
npm test
npm run lint
```

Please make sure to follow the existing code style and add tests for any new functionality.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
