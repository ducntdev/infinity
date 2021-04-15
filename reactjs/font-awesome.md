# Install package
npm i --save @fortawesome/fontawesome-svg-core
npm install --save @fortawesome/free-solid-svg-icons
npm install --save @fortawesome/react-fontawesome
npm i @fortawesome/free-brands-svg-icons

# import vào App.jsx
import { fab } from '@fortawesome/free-brands-svg-icons';
import { faCheckSquare, faCoffee } from '@fortawesome/free-solid-svg-icons';
import { FontAwesomeIcon } from '../node_modules/@fortawesome/react-fontawesome';

library.add(fab, faCheckSquare, faCoffee);

#
