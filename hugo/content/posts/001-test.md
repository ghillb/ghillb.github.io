---
title: "Test post"
date: 2023-02-13T20:27:24+01:00
draft: true
tags: ["test", "markdown", "hugo", "by gh"]
showToc: true
tocOpen: false
showReadingTime: true
showWordCount: true
cover:
    image: "https://user-images.githubusercontent.com/35503959/218551906-df791898-5f45-44cc-a63b-b75bfc286d11.png#center"
    alt: "coding space monkey"
    caption: "the bliss of flow"
    relative: false # set true for bundles
    hidden: false # hide on post
---

# Test post

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris tincidunt eleifend sollicitudin. Pellentesque volutpat erat eu facilisis mollis. Proin lacus neque, viverra quis erat et, placerat hendrerit enim. Quisque id feugiat est. Interdum et malesuada fames ac ante ipsum primis in faucibus. Proin lacus magna, rutrum in fermentum quis, pharetra non felis. Aliquam in pharetra enim, non finibus erat. Quisque efficitur ultrices dolor, in venenatis augue. Nullam eget ex vel ligula tristique egestas. Aliquam in quam sed ipsum porttitor tincidunt.

## Some Python code
```python
import numpy as np


def gelu(x):
    return 0.5 * x * (1 + np.tanh(np.sqrt(2 / np.pi) * (x + 0.044715 * x**3)))


def softmax(x):
    exp_x = np.exp(x - np.max(x, axis=-1, keepdims=True))
    return exp_x / np.sum(exp_x, axis=-1, keepdims=True)
```

Sed blandit lacus vitae libero mollis venenatis. Nulla ac felis non velit fringilla ultrices. Morbi dapibus ligula ut mauris posuere commodo. Vivamus varius arcu in felis fermentum mattis. Nullam aliquam sem id urna ultricies, at bibendum massa ullamcorper. Suspendisse sit amet tellus interdum, bibendum nisl non, mollis dui. Integer aliquam suscipit tortor non malesuada.

Sed quis egestas mi. Curabitur faucibus enim vitae ullamcorper sodales. Etiam egestas nibh in ultricies tristique. Quisque felis lorem, feugiat id turpis quis, blandit pretium ligula. Nam tempor tincidunt elit sit amet dapibus. Ut facilisis ac arcu et tempor. Maecenas faucibus felis quis bibendum egestas. Morbi bibendum sit amet est tristique tempus. Aliquam tincidunt odio id congue tincidunt. Fusce pretium odio vitae efficitur viverra.

![medieval tapestry solar system](https://user-images.githubusercontent.com/35503959/218560623-a2525119-c12c-4e68-95b1-5792de3278e4.png)

Phasellus venenatis ligula quis nisi vulputate iaculis. Nam id tortor libero. Ut ac sapien et lectus porttitor euismod. Sed quis vestibulum metus. Sed consectetur euismod enim, eget semper massa faucibus at. Aenean ac ultrices est, sed hendrerit dolor. Vestibulum ac metus vel nulla ultrices laoreet. Nulla fringilla volutpat ipsum pretium faucibus. Phasellus nisi dolor, viverra et consequat nec, fermentum in odio. Aliquam molestie justo at dolor sagittis, ut faucibus nisi dapibus. Nam fringilla magna sit amet massa congue vulputate id pretium mi. Nulla facilisis tortor nec odio dignissim luctus.

## Some Lua code
```lua
function utils.shorten_path(path)
  local Path = require("plenary.path")
  path = Path:new(path)

  local shortened_path = path:shorten(1)

  if has_windows() and path:is_absolute() then
    return adjust_absolute_path_head_for_windows(shortened_path)
  else
    return shortened_path
  end
end
```
In vitae pellentesque orci. Curabitur vulputate rhoncus tellus. Proin tincidunt ante vel ultrices suscipit. Mauris eget libero vitae lectus interdum dignissim vel et purus. Cras id massa interdum, suscipit eros nec, viverra elit. Sed ante dui, euismod id pharetra vitae, mollis non erat. Sed laoreet magna vel sem ornare eleifend. Nam accumsan lacinia elementum. Fusce interdum erat suscipit lectus scelerisque, at pulvinar urna vulputate. Sed id sapien orci. Curabitur ultricies, orci eget euismod pellentesque, urna nisi auctor odio, eget imperdiet purus mi vitae turpis. Aenean vitae lacus vulputate, fermentum est volutpat, pellentesque ligula. Morbi fringilla facilisis arcu, in accumsan dui mollis rutrum. Sed vel dictum risus. Nulla facilisi. Vestibulum mi leo, scelerisque vel ligula sit amet, gravida viverra risus. 

