# DroidEmail

Simple email markup with responsive support. Just copy the code and start the markup. Basic stuff is already coded.

## Couple tips&tricks

#### Inline CSS

Yep, no kidding. All the CSS should be inline CSS. Except for CSS in <head> (read below).

#### No @FontFace, No JS

Yep, they won't work. Don't even waste your time on that.

#### Strict DOCTYPE

Gmail and couple other web-services would like to have a Strict DOCTYPE. If other is specified - it will be replaced.

#### CSS in head tag

Please keep the header more than 1023 symbols. Otherwise the email will be cut on the iOS devices in the default Apple's Mail app.

#### What is body[yahoo] in the Media Queries?

Just keep it for Yahoo!Mail. Don't forget to specify the selectors like that for responsive in order to email be responsive on mobile devices.

#### Reserved space around the email

Sometimes it's very nice to have borders on the email, especially if you're viewing it on mobile. Try to keep them if that won't make your design terrible.

#### Use preheader block

For email previews on the most of the desktop and mobile clients it's very handy to have important text of the email, rather links to your social networks. Put the body text of the email in that block.

#### Set alt="" text for all the images

Sometimes images won't load on mobile devices or they can be disabled by user (very rare, but happens). Include alt="" texts - love your clients.

## License

Licenced under MIT: <http://opensource.org/licenses/MIT>.

## Got questions?

Feel free to contact us regarding DroidEmail via [twitter](http://twitter.com/droidlabs) or [email](mailto:ilya@droidlabs.pro).

## Thanks for using DroidEmail

Cheers,
[DroidLabs](http://droidlabs.pro).