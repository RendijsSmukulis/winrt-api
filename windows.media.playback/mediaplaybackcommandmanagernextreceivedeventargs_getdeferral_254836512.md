---
-api-id: M:Windows.Media.Playback.MediaPlaybackCommandManagerNextReceivedEventArgs.GetDeferral
-api-type: winrt method
---

<!-- Method syntax
public Windows.Foundation.Deferral GetDeferral()
-->

# Windows.Media.Playback.MediaPlaybackCommandManagerNextReceivedEventArgs.GetDeferral

## -description
Gets a [Deferral](../windows.foundation/deferral.md) object that causes the system to wait for you to perform asynchronous operations, such as creating a new [MediaPlaybackItem](mediaplaybackitem.md) from a network source, before it continues processing the **Next** command.

## -returns
The deferral object.

## -remarks
Call [Complete](../windows.foundation/deferral_complete.md) when your asynchronous operations are complete to signal the system to continue.

## -examples

## -see-also
