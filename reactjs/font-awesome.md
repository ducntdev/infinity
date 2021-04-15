# Installing packages
``` Shell Session
npm i @fortawesome/fontawesome-svg-core 
      @fortawesome/free-solid-svg-icons 
      @fortawesome/react-fontawesome 
      @fortawesome/free-brands-svg-icons
```

# Declare to App.jsx
``` jsx
import { fab } from '@fortawesome/free-brands-svg-icons'; 
import { faCheckSquare, faCoffee } from '@fortawesome/free-solid-svg-icons'; 
import { FontAwesomeIcon } from '../node_modules/@fortawesome/react-fontawesome'; 

library.add(fab, faCheckSquare, faCoffee);
```

# Usage
``` jsx
<FontAwesomeIcon icon={['fab', 'facebook']} />
```

# Find icon
https://fontawesome.com/icons?d=gallery&p=2&q=fac&s=brands
![image](https://user-images.githubusercontent.com/72643469/114815972-79b46500-9de1-11eb-9467-4cc7e87808e9.png)
