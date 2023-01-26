# Hello Triangle Breakdown



## Initialisation

**> Enumerate instance extensions**

vkEnumerateInstanceExtensionsProperties

**> Check requested extensions are supported**

**> Enumerate instance layer properties**

vkEnumerateInstanceLayerProperties

**> Check requested layers are supported**

**> Create Vulkan instance**

vkCreateInstance

**> Create window surface to use**

Store window size for later swapchain initialisation

**> Initialise Vulkan physical device**

vkEnumeratePhysicalDevices
(iterate through physical devices)
    (get physical device queue family properties)

**> Enumerate device extension properties**

vkEnumerateDeviceExtensionProperties

**> Create physical device with queue**

vkCreateDevice

**> Get device surface supported capabilities and formats**

**> Create SwapChain telling it the format based on the OS provided surface**

**> Grab the SwapChain images and initialise them**

(per swapchain image)
    (create fence)
    (create command pool)
    (create image view for swap chain image)

## Update

## Shutdown
