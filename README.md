
## Installing Prerequisites (Windows)

<details>
<summary>Install Ruby</summary>

1. Download the RubyInstaller from https://rubyinstaller.org/downloads/. Use the bolded version in the "WITH DEVKIT" section.

    ![ruby1.png](./.github/img/ruby1.png)

2. Run the installer
3. Accept the licence agreement and click Next

    ![ruby2.png](./.github/img/ruby2.png)

4. Make sure "Add Ruby executables to your PATH" is checked and click Install

    ![ruby3.png](./.github/img/ruby3.png)

5. Make sure "MSYS2 development toolchain" is checked and click Next

    ![ruby4.png](./.github/img/ruby4.png)

6. Wait for the installer to finish

    ![ruby5.png](./.github/img/ruby5.png)

7. Make sure "Run 'ridk install' to setup MSYS2 and development toolchain" is checked and click Finish
    
    ![ruby6.png](./.github/img/ruby6.png)

8. A new window should pop up that looks like this. Hit the Enter key to continue.

    ![ruby7.png](./.github/img/ruby7.png)

9. After a while you should get a message that says "Install MSYS2 and MINGW development toolchain succeeded". Hit the Enter key to close the window

    ![ruby8.png](./.github/img/ruby8.png)

</details>

<details>
<summary>Install Bundler</summary>

1. Open a new command prompt
2. Run `gem install bundler`

</details>

## Setup

1. Clone the repo
   - `git clone git@github.com:Tschrock/bedrock-addon-docs.git`
   - `cd bedrock-addon-docs`
2. Install project dependencies
   - `bundle install`
3. Start the development server
   - `bundle exec jekyll serve`