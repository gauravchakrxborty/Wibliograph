Value properties

These global properties return a simple value. They have no properties or methods.

-----------------------------------------------------------------------------------

#globalThis#

JavaScript Demo: Standard built-in objects - globalThis

function canMakeHTTPRequest() {
  return typeof globalThis.XMLHttpRequest === 'function';
}

console.log(canMakeHTTPRequest());
// Expected output (in a browser): true

-----------------------------------------------------------------------------------