# Ultimate Custom MFE Guide

Hello, a few weeks ago i write this [topic](https://discuss.openedx.org/t/adding-custom-components-in-a-column-mfe-gradebook/13071/9) and since the last post i have spend very much time developing my custom MFE, and here ill try to explain every step of development.
In this guide, you will be able to build your custom MFE for OpenedX 

# Contents
- Setting Environment
- 



# Setting Environment
First off all, im using Tutor Quince you can follow [this documentation](https://docs.tutor.edly.io/) to install it too. Im also using [Tutor Version Manager](https://github.com/eduNEXT/tvm),  it helps a lot for development if you need to run various versions of tutor in you machine.

After tutor instalation you have to clone the [frontend-template-application](https://github.com/openedx/frontend-template-application) from the repository. When you clone it, you can simple follow the README and see the hello-world by running `npm install` and `npm start`. In that way you will run the template application **outside tutor**, so you can edit the frontend-template-aplication code and develop in a faster way. 

You will also may want to customize MFEs that already exist in edX, [here](https://github.com/overhangio/tutor-mfe#mfe-development) you have many MFEs that you can customize. Lets get Gradebook as example.

Unlike a brand new MFE, this MFEs can be mounted in edX and you can hot-reload while you develop. To do this, first you clone the repo, in this case ill clone gradebook, and then, you can use `tutor mounts path/to/gradebook-folder`. This way you can access apps.local.edly.io:

**Intagrating your MFE with edX:**


