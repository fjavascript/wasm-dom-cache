# wasm-dom-cache
proxy all requests to document, maintain a hash table of dom in .wasm, compare request with the hash table, do nothing on match, update dom and the hashtable otherwise.
