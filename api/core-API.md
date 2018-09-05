```javascript

/**
 * Generate mnemonic 
 * @method mnemonic
 * @for Base
 * @param {void}
 * @return {string} 12 mnemonic
 */
Client.mnemonic()


/**
 * Generate a root private key based on the mnemonic
 * @method xPrivKey
 * @for Base
 * @param {string}  Mnemonic 
 * @return {string} private key
 */
Client.xPrivKey(mnemonic)


/**
 * Generate root public key 
 * @method xPubKey
 * @for Base
 * @param {string}  private key 
 * @return {string} root public key
 */
Client.xPubKey(xPrivKey)


/**
 * Generate wallet public key 
 * @method walletPubKey
 * @for Base
 * @param {string}  
 * @param {int}     index 0-
 * @return {string} 
 */
Client.walletPubKey(xPrivKey, num)

