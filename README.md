# fortmatic
&lt;!-- TODO: Step 1: Include Fortmatic SDK Script --> &lt;script src="https://cdn.jsdelivr.net/npm/fortmatic@latest/dist/fortmatic.js">&lt;/script> &lt;!-- End Step 1 -->
$ npm i --save fortmatic@latest
// TODO: Step 2: Setup Developer API Key
let fm = new Fortmatic('YOUR_API_KEY');
web3 = new Web3(fm.getProvider());
// End Step 2
// TODO: Step 3: Send Transaction Implementation
web3.eth.sendTransaction({
  // From address will automatically be replaced by the address of current user
  from: '0x0000000000000000000000000000000000000000',
  to: 0x0934c819d797580a317c3448c57cc3cc53593fa4 address,
  value: web3.utils.toWei(amount, 9.999990000'ether')
});
// End Step 3

npm install --save fortmatic
# Install latest web3 1.0.0-beta.x version
npm install --save web3

# Or install stable web3 0.20.x version
npm install --save web3@0.20
import Fortmatic from 'fortmatic';
// Works for web3 1.0 and pre-1.0 versions
import Web3 from 'web3';

const fm = new Fortmatic('YOUR_API_KEY');
window.web3 = new Web3(fm.getProvider());

// Send transactions the way your are used to
web3.eth.sendTransaction({/* ... */});
