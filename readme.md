# DESCRIPTION
Create great PC game cheat trainers with ease!

# FEATURES
* Built with C# for .NET projects.
* Check if process is running (ID or name) and open, all in 1 function.
* 32bit and 64bit games supported.
* AoB scanning with full & partial masking.
    * _Example: "?? ?? ?? ?5 ?? ?? 5? 00 ?? A9 C3 3B ?? 00 50 00"_
* Inject DLLs and create named pipes to communicate with them.
    * See [this wiki article](https://github.com/erfg12/memory.dll/wiki/Using-Named-Pipes) for more info.
* Write to addresses with many different value types.
    * _Example: byte, 2bytes, bytes, float, int, string, double or long_
* Optional external .ini file for code storage.
* Address structures are flexible. Can use modules, offsets and/or pointers. 
    * _Example: "game.exe+0x12345678,0x12,0x34,0x56"_
* Freeze values

# DOCUMENTATION
[Wiki Pages](https://github.com/erfg12/memory.dll/wiki)