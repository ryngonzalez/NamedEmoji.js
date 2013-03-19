# NamedEmoji.js

A port of [jugyo's](https://github.com/jugyo) [named_emoji](https://github.com/jugyo/named_emoji) Ruby gem, now written in Javascript. Written with some knowledge about handling UCS-2 encoding from [punycode.js](https://github.com/bestiejs/punycode.js/blob/a6ea357aae89c90733dedd83cc4dac6982a69478/punycode.js#L128-147).

Who doesn't like emoji?

## Compatibility

On iOS devices, only renders in Safari natively. Should be used with something like [emojify.js](https://github.com/hassankhan/emojify.js) to handle compatibility everywhere.

## Usage

    Emoji.get("smile") # => 😄
    Emoji.get("grin")  # => 😁
    Emoji.get("poop")  # => 💩

