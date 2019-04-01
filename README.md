react-mobile-swiper
================

>a simple react-swiper component <a href="https://hardtogit.github.io/react-mobile-swiper/example/build/index.html">https://hardtogit.github.io/react-mobile-swiper/example/build/index.html</a>
## Demo

<img src="https://raw.githubusercontent.com/hardtogit/react-mobile-swiper/master/example/src/assets/img/demo.gif" alt="YaMOrzoWHp.jpg">
## get start

#### step one
```bash
clone or down this project
```
#### the second step
```bash
cd example
```
#### the third step
```bash
npm install
```
#### finally
```bash
npm start
```
## how to use

### Example with defaults
#### install
```bash
npm intsall --save react-mobile-swiper
```
#### Creating an example component:
```javascript
import React,{Component} from 'react';
import Swiper from 'react-mobile-swiper';
const animateTypes=Swiper.animateTypes;
class Example extents Component{
  render: function() {
    return (
      <Swiper type={animateTypes.DEFAULT} loop>
       <div><img src=''/></div>
       <div><img src=''/><div>
      </Swiper>
    );
  },
};
export default Example;

