# Hello triangle

Draws a single triangle in the window

## Flow

- Enumerate instance extension properties
	- Check instance supports required extensions
- Enumerate instance layer properties
	- Check instance supports required layers
- Create instance
- Enumerate physical devices
- Iterate over physical device properties and find the best fit
	- Enumerate device extension properties
	- does it contain a graphics queue
- Create device - with queue info
- Get device queue
- Init swapchain
	- Get physical device surface capabilities - with screen surface
	- Enumerate physical device surface formats
	- Pick a format
	- Determine number of images to use in swapchain
	- 
- Init render pass
- Init pipeline
- Init frame buffers