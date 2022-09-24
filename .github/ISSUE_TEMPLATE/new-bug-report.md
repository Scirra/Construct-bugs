---
name: Dictionary Spacing Issue
about: Reporting a bug, where copy and pasting in a Dictionary causes invisbile spaces
title: 'Dictionary Spacing Issue'
labels: 'Dictionary'
assignees: ''

---

<!-- You must use this template or your issue will be closed without investigation. Please see the guidelines. -->

## Problem description

<!-- Enter a concise description of your problem here -->

When copy and pasting Key names in the dictionary, Construct 3 will add a space (\n) after the copied Key name. This is NOT visible in the Dictionary Editor, and when any extra spaces in the Key text box are deleted, the space persists.

## Attach a .c3p

<!-- A minimal Construct 3 project (.c3p) is required to be attached. Your issue will likely be closed without investigation if you don't provide one. Please see the guidelines -->

[Dictionary Test.c3p.zip](https://github.com/Scirra/Construct-3-bugs/files/9639306/Dictionary.Test.c3p.zip)

## Steps to reproduce

<!-- These steps are essential for us to be able to help you. Usually it is impossible to investigate reports unless they include steps we can follow ourselves, so please do your best to provide specific steps. There is no need to explain how you made the attached project - just explain what to do to with the project to observe the issue. -->

1. Upon preview loaded, click the different colored squares. (The Red and Blue are fine and update the letters in order.)
2. Notice the Green box will first change the text to A, then it will say 0, then C, then D, etc.
3. With the Yellow box, the first text will say YY, then it will say 0 for the remaining clicks (where it should say 'ZZ', 'AA', etc).
4. By outputting the JSON file to the console, you can see that there are some Keys that have an added space in the name. That space is NOT present in the Key text boxes in the Dictionary. This only occurs when the Key text is copy and pasted, then changed for another Key box.

## Observed result

<!-- What do you see happen? -->

In the code, a space is being added when copy and pasting a previously used Key name into another box then altering that Key name. This space is NOT present in the Key name box, but IS present in the console code.

## Expected result

<!-- What did you expect to happen instead? -->

Upon clicking any of the boxes, the Instance Variable for each (MessageNumber) should update, be added to the end of "DictionaryName", then the Dictionary should pull up the Value using DictionaryName+MessageNumber as the Key. Then the text box in the center should change to the string in the Value for the corresponding Key.

## More details
<!-- Providing this information will make it more likely the issue you are reporting can be fixed quickly. -->

<!-- It's helpful to test as many browsers, platforms or export options as possible. For example an issue occurs in an Android app, does it also occur in Chrome on Windows? How about Firefox? etc. -->

I have tested this in both Chrome and Safari, and have learned that if you completely delete the text from the Key box, click out of it to deselect it, then retype the same exact name in that Key text box, the additional space is not present. However, if you copy and paste a previous Key text box entry, and then edit the text to be anything WITHOUT deleting it entirely and clicking out of the box, the space persists in the console representation of the JSON file.

**Affected browsers/platforms:** <!-- Chrome/Firefox/Safari, Windows/macOS/Android, etc -->

<!-- Identifying the first version the issue started happening can help resolve the issue more quickly. -->

Safari, Chrome

**First affected release:** <!-- e.g. worked in r122 but broke in r123 -->

R308.2

## System details

<!-- If you see a crash report dialog, please copy and paste it to where it says "PASTE HERE" below. -->
<!-- Otherwise please go to Menu > About > Platform information and paste that information there instead. -->

Platform information Product: Construct 3 r308.2 (stable) Browser: Safari 14.1.2 Browser engine: WebKit Context: browser Operating system: macOS 10.15.7 Device type: desktop Device pixel ratio: 2 Logical CPU cores: (unavailable, defaulting to 2) Approx. device memory: (unavailable) User agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/14.1.2 Safari/605.1.15 Language setting: en-US
Local storage Storage quota (approx): (status unavailable) Storage usage (approx): (status unavailable) Persistant storage: (status unavailable)
Browser support notes This list contains missing features that are not required, but could improve performance or user experience if supported.
Rendering multiple on-screen Layout Views is slow in Safari due to bug 177132 CSS containment is not supported. Editor performance may be significantly degraded. The element is not supported. A polyfill is in use. Web Animations are not supported. Animations are disabled. WebGL 2+ is not supported. Rendering quality and features may be affected. ImageBitmap is not supported. Texture loading performance may be degraded. Idle callbacks are not supported. Background loading performance may be degraded. Determining input device capabilities is not supported. Persistent storage is not available. Local storage could be deleted by the browser. Storage quota estimate is unavailable. WebGL information Version string: WebGL 1.0 Numeric version: 1 Supports NPOT textures: partial Supports GPU profiling: no Supports highp precision: yes Vendor: Apple Inc. Renderer: Apple GPU Major performance caveat: no Maximum texture size: 16384 Point size range: 1 to 64 Extensions:
EXT_blend_minmax EXT_sRGB EXT_frag_depth OES_texture_float OES_texture_float_linear OES_texture_half_float OES_texture_half_float_linear OES_standard_derivatives EXT_shader_texture_lod EXT_texture_compression_rgtc EXT_texture_filter_anisotropic OES_vertex_array_object OES_element_index_uint OES_fbo_render_mipmap WEBGL_lose_context WEBGL_compressed_texture_s3tc WEBGL_compressed_texture_s3tc_srgb WEBGL_depth_texture WEBGL_draw_buffers ANGLE_instanced_arrays WEBGL_debug_shaders WEBGL_debug_renderer_info EXT_color_buffer_half_float EXT_float_blend WEBGL_color_buffer_float KHR_parallel_shader_compile Audio information System sample rate: 44100 Hz Output channels: 2 Output interpretation: speakers Supported decode formats:
WebM Vorbis (audio/webm; codecs=vorbis) MPEG-4 AAC (audio/mp4; codecs=mp4a.40.5) MP3 (audio/mpeg) FLAC (audio/flac) Supported encode formats:
MPEG-4 AAC (audio/mp4; codecs=mp4a.40.5) Video information Supported decode formats:
WebM VP9 (video/webm; codecs=vp9) WebM VP8 (video/webm; codecs=vp8) H.264 (video/mp4; codecs=avc1.42E01E) Supported encode formats:
H.264 (video/mp4; codecs=avc1.42E01E)


<details><summary>View details</summary>

PASTE HERE

</details>
