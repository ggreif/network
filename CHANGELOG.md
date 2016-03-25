## Version 2.7

 * Removed deprecated aliases from `Network.Socket`:
   * `bindSocket` -> `bind`
   * `sClose` -> `close`
   * `sIsConnected` -> `isConnected`
   * `sIsBound` -> `isBound`
   * `sIsListening` -> `isListening`
   * `sIsReadable` -> `isReadable`
   * `sIsWritable` -> `isWritable`

## Version 2.6.2.1

 * Regenerate configure and `HsNetworkConfig.h.in`.

 * Better detection of CAN sockets.

## Version 2.6.2.0

 * Add support for `TCP_USER_TIMEOUT`.

 * Don't conditionally export the `SockAddr` constructors.

 * Add `isSupportSockAddr` to allow checking for supported address types
   at runtime.
