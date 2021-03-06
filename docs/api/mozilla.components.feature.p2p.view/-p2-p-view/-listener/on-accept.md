[android-components](../../../index.md) / [mozilla.components.feature.p2p.view](../../index.md) / [P2PView](../index.md) / [Listener](index.md) / [onAccept](./on-accept.md)

# onAccept

`abstract fun onAccept(token: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) [(source)](https://github.com/mozilla-mobile/android-components/blob/master/components/feature/p2p/src/main/java/mozilla/components/feature/p2p/view/P2PView.kt#L136)

Handles a decision to accept the connection specified by the given token. The value
of the token is what was passed to [authenticate](../authenticate.md).

### Parameters

`token` - a short string uniquely identifying a connection between two devices