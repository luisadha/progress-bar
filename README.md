# progress-bar

Animated progressbar similar to DHCP, add animation to your scripts using `source'

[![Preview](https://github.com/luisadha/progress-bar/blob/db9cded2f800f6aea8baf4afb9c4f5ce4854f7b9/thumb.jpg)](https://youtube.com/shorts/GtcwPmhZ62k?feature=share)

## Usage:

    1. Source this file on your shell script

    2. Start the animation:

       start_animation "[parameter1]" -> this parameter will display your message

          e.g.: start_animation "Loading" # "Installing", "Copying" and etc.

    3. Run your command

    4. stop_animation "[parameter1]" -> this parameter your command's exit status

          e.g.: stop_animation $? || exit 1

 Also see: test.sh


## Reference 

- https://github.com/tlatsas/bash-spinner

- https://github.com/mayTermux/myTermux

- https://github.com/luisadha/progsche

## Huge thank

* Xshin (My inpsirtation)

* Alif-Hitagi (Tester)

## MIT License 
