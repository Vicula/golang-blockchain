# Golang Blockchain

### In this tutorial, we add a Wallet Module to our Blockchain app. 

## Run `go run main.go` to run the app, run `go build main.go` to build an executable file.

### Check out the Youtube Tutorial for this [Go Program](https://youtu.be/O9rDas-0s2c). Here is our [Youtube Channel](https://www.youtube.com/channel/UCYqCZOwHbnPwyjawKfE21wg) Subscribe for more content.

### Check out our blog at [tensor-programming.com](http://tensor-programming.com/).

### Our [Twitter](https://twitter.com/TensorProgram), our [facebook](https://www.facebook.com/Tensor-Programming-1197847143611799/) and our [Steemit](https://steemit.com/@tensor).


Well, if I was going to use this as a template for a real blockchain then I would likely refactor the network module first and then I would clean up the core blockchain module quite a bit. I might switch from badger to leveldb at some point and perhaps split everything into microservices.  Its really going to depend though on what it is you want to accomplish.  

I will caution you though.  If you plan to use this code for a real chain, you will likely run into a ton of painful security problems.  It would be better to just take what you've learned and expand that into your own code.  It would also help to just clean things up and make things more clear to save a ton of development pain in the future. 

Anyhow, good luck.  Glad you found the series useful and glad it helped you learn go.
