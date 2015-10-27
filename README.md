**Note: justinj's snipmate snippets originally ported to ES6 by bentayloruk, I only use Ultisnips so those are the only ones I've tested**


vim-react-es6-snippets
==================

A set of snippets for Vim to work with Facebook's [React](http://facebook.github.io/react/) library.

A direct port of the awesome snippets from
[justinj/vim-react-snippets](https://github.com/justinj/vim-react-snippets).

Requires [UltiSnips](https://github.com/SirVer/ultisnips).

Installation
============

Use your preferred (neo)vim plugin installation method or just copy the snippets over to the relevant folder.

Usage
=====

Within any Javascript or JSX file, you should be able to do the following:

(in insert mode)
```
gdp<Tab>
```

expanding to

```
getDefaultProps() {
    return {

    };
},
```

And a bunch of others!

You may have to set `g:UltiSnipsExpandTrigger` and `g:UltiSnipsJumpForwardTrigger`, depending on which other tab-based plugins you have installed. I personally use Control+j. Check the UltiSnips help page for more info and `UltiSnips/javascript.snippets` in this repo to see the full snippet list.
