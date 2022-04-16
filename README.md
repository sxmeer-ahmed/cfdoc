![CF Doctor](cfdoc-demo.gif)

# Download
There's no installation, setup or toolchain required. 
Download the binaries for your respective system, and rename it to `cfdoc`.
Open a terminal/command-prompt inside that folder, and everything should work.

# Global Access
If you want to run the `cfdoc` command from anywhere in your terminal, you need
to add the binary to your PATH.

On UNIX based systems, this should suffice.
```
sudo cp ./cfdoc /usr/bin
```

Verify using
```
which cfdoc
```

On Windows, add the folder where the executable is downloaded to your path.
Here's a [reference](https://zwbetz.com/how-to-add-a-binary-to-your-path-on-macos-linux-windows/) on how to do that.

**NOTE**: You'd need to use `./cfdoc` if you haven't added it to your PATH.

# Usage
```
cfdoc help
```