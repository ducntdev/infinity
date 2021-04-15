# References
https://www.npmjs.com/package/react-multi-carousel
<br/>
https://w3js.com/react-multi-carousel

# Installing packages
``` shell session
npm i react-multi-carousel
```

# Usage
``` jsx
import Carousel from "react-multi-carousel";
import 'react-multi-carousel/lib/styles.css';

const images = [
  // image links
]

const responsive = {
  desktop: {
    breakpoint: { max: 3000, min: 1024 },
    items: 3,
    paritialVisibilityGutter: 60
  },
  tablet: {
    breakpoint: { max: 1024, min: 464 },
    items: 2,
    paritialVisibilityGutter: 50
  },
  mobile: {
    breakpoint: { max: 464, min: 0 },
    items: 1,
    paritialVisibilityGutter: 30
  }
}

const MultiCarosel = ({ deviceType }) => {
  return (
    <Carousel
      ssr
      partialVisbile
      // deviceType={deviceType}
      itemClass="image-item"
      responsive={responsive}
      infinite
    >
      {images.slice(0, 5).map((image, index) => 
        // Items here
      )}
    </Carousel>
  );
};
```
