# 💤💤💤💤 fork lazy-route 💤💤💤

# lazy-route - Lazy route loading for React Router 4 through System.import

#### Dependencies and requirements

This component only works with React Router 4 and Webpack 2 (because of System.import).

#### Usage

Installation:

`npm install route-lazy` or `yarn add route-lazy`

How to use with React Router 4:

```javascript
import {Match} from 'react-router'
import RouteLazy from 'route-lazy'

<Match 
  pattern="/myroute"
  render={(props) => <RouteLazy {...props} component={import('./myComponent')} />}
/>
```

#### Upcoming features
The component works, but I have yet to add tests and some polish to it,
the plan is to add a customizable loader etc.

### Thinks

[Chih-Hsuan Fan](https://github.com/pc035860)
[Martin](https://github.com/mhaagens)
