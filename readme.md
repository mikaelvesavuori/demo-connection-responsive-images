# Demo: Connection-Responsive Images

This demonstrates setting image URLs dynamically based on the NetworkInformation API's connection type. This pattern should be combined with a modern Picture element for responsive images, thus also looking at the viewport size.

Safari 11.1.2 will not currently support this, but Chrome 68 will. Safari will fall back to a medium quality image and Chrome will use a progressively higher quality image, based on connection speed. To emulate this effect, use the Network panel to throttle the speed.
