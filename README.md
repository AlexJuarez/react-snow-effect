#React Snow Effect Component

###How do I use this?
```
npm install react-snow-effect
```

Include the component in your main app component outside of any containers.
```js
// MyApp.js

var React = require('react');
var Snow = require('react-snow-effect');

var MyApp = React.createClass({
	render: function() {
		return (
			<div className='my-fancy-app'>
				<Snow />
				<div className='container'>
					{appContents}
				</div>
			</div>
		)
	}
}

module.exports = MyApp;
```

Disclaimer! This code borrows heavily from a lovely [html5-canvas-snow-effect] (http://thecodeplayer.com/walkthrough/html5-canvas-snow-effect) tutorial

If you have any problems, please let me know. This is my first npm package and I'd love for it to work for everyone!

:snowflake: :snowflake: Happy Holidays! :snowman: :snowflake: :snowflake:

                         *  .  *
                       . _\/ \/_ .
                        \  \ /  /             .      .   
          ..    ..    -==>: X :<==-           _\/  \/_
          '\    /'      / _/ \_ \              _\/\/_
            \\//       '  /\ /\  '         _\_\_\/\/_/_/_
       _.__\\\///__._    *  '  *            / /_/\/\_\ \
        '  ///\\\  '                           _/\/\_
            //\\                               /\  /\ 
          ./    \.             ._    _.       '      '
          ''    ''             (_)  (_)                  <> \  / <>
                                .\::/.                   \_\/  \/_/ 
               .:.          _.=._\\//_.=._                  \\//
          ..   \o/   ..      '=' //\\ '='             _<>_\_\<>/_/_<>_
          :o|   |   |o:         '/::\'                 <> / /<>\ \ <>
           ~ '. ' .' ~         (_)  (_)      _    _       _ //\\ _
               >O<             '      '     /_/  \_\     / /\  /\ \
           _ .' . '. _                        \\//       <> /  \ <>
          :o|   |   |o:                   /\_\\><//_/\
          ''   /o\   ''     '.|  |.'      \/ //><\\ \/
               ':'        . ~~\  /~~ .       _//\\_
                          _\_._\/_._/_      \_\  /_/ 
                           / ' /\ ' \                   \o/
           o              ' __/  \__ '              _o/.:|:.\o_
      o    :    o         ' .'|  |'.                  .\:|:/.
        '.\'/.'                 .                 -=>>::>o<::<<=-
        :->@<-:                 :                   _ '/:|:\' _
        .'/.\'.           '.___/*\___.'              o\':|:'/o 
      o    :    o           \* \ / */                   /o\
           o                 >--X--<
                            /*_/ \_*\
                          .'   \*/   '.
                                :
                                '
