# Srch
Small utility for searching for anything in several search engines

### Installation 
With the following command you will get all of the files:

``` $ git clone https://github.com/AlexCul/Srch.git && cd Srch/ ```

Now for installation you have to execute this command as root user:

``` # chmod +x install && ./install ```

### Usage
With the following command you can

``` srch <search_engine_reduction> your question here ```

or if you want to open some website(s) directly you can use "-l"/"--link" argument:

``` srch --link youtube.com facebook.com etc. ```

**Note no. 1**: If you have written your question and websites with "-l" argument it'll not work correct.

So instead of this:

``` $ srch g my question here -l y ```

use this:

``` $ srch g my question && srch -l y ```

**Note no. 2**: You can execute:

``` # chmod +x add_alias && ./add_alias ```

Then you can type just:

``` $ <search_engine_reduction> your question here ```

``` $ o websites.you.want ``` 

``` $ o saved_file/you/wanttoopen.html ```


### Available search engines:
1. Baidu ("bdu")
2. Bing ("bg")
3. DuckDuckGo ("duck")
4. Google ("g")
5. Yahoo! ("yah")
6. Yandex ("yx")
7. Whatever you want to add!
