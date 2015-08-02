﻿#summary Provides release notes for new versions of SVG Web
#labels Featured

# Introduction #

This page provides release notes for release of SVG Web

## Instructions for Updating This Page ##

At the top of this list is the entry 'In Development'. This will track the head of the repository with each issue that is fixed. As you fix issues just update this bullet list, where each bullet list should be in the form:

  * Issue X: "Title of Issue"

When we are ready to do a release, we can simply change the 'In Development' title to the release name, which will just be the date (svgweb-YEAR-MONTH-DAY.zip), followed by the final Subversion release number that the release was built from. For example, if we create a release on July 28th, 2009 from Subversion release [r650](https://code.google.com/p/svgweb/source/detail?r=650), we would show:

svgweb-2009-07-28.zip ([r650](https://code.google.com/p/svgweb/source/detail?r=650))
  * [Issue 10](https://code.google.com/p/svgweb/issues/detail?id=10): "Some Issue Title"

The 'Breaking Changes' section should contain a bullet list of any breaking changes this release might introduce to those upgrading their installations.

# Releases #

## In Development ##
  * [Issue 605](https://code.google.com/p/svgweb/issues/detail?id=605): script src="svg.js" does not work without data-path="./"


## svgweb-2011-02-03-Lurker-Above ([r1332](https://code.google.com/p/svgweb/source/detail?r=1332)) ##
  * [Issue 576](https://code.google.com/p/svgweb/issues/detail?id=576): animation of rotate attribute causes redraw
  * [Issue 577](https://code.google.com/p/svgweb/issues/detail?id=577): Start animations in order and respect activation priority
  * [Issue 578](https://code.google.com/p/svgweb/issues/detail?id=578): Duplicate event listeners added for animation events
  * [Issue 511](https://code.google.com/p/svgweb/issues/detail?id=511): Keyboard events are not supported properly (Part Two - keyup, misc fixes)
  * [Issue 579](https://code.google.com/p/svgweb/issues/detail?id=579): Old text still displayed after clearing text node content
  * [Issue 239](https://code.google.com/p/svgweb/issues/detail?id=239): Implement mpath: motion along a path
  * [Issue 541](https://code.google.com/p/svgweb/issues/detail?id=541): Support animateMotion
  * [Issue 548](https://code.google.com/p/svgweb/issues/detail?id=548): offset lineargradient works for rect and circle, but not for polygon, ellipse and path
  * [Issue 580](https://code.google.com/p/svgweb/issues/detail?id=580): document firstChild reverts attached status on root element
  * [Issue 583](https://code.google.com/p/svgweb/issues/detail?id=583): Elements returned from getElementsByTagName emit no `_handler` errors (regression from [Issue 536](https://code.google.com/p/svgweb/issues/detail?id=536),[r1214](https://code.google.com/p/svgweb/source/detail?r=1214))
  * [Issue 368](https://code.google.com/p/svgweb/issues/detail?id=368): Make sure SVG Web works in iframes
  * [Issue 567](https://code.google.com/p/svgweb/issues/detail?id=567): Fails to display anything for Illustrator-generated SVG files
  * [Issue 574](https://code.google.com/p/svgweb/issues/detail?id=574): Flash version 10 requirements need update
  * [Issue 565](https://code.google.com/p/svgweb/issues/detail?id=565): Default to src path when no data-path
  * [Issue 146](https://code.google.com/p/svgweb/issues/detail?id=146): svgweb.removeChild of object on page unload causes exception, getAttribute fails
  * [Issue 592](https://code.google.com/p/svgweb/issues/detail?id=592): getBBox throws exception if called before flash loaded
  * [Issue 591](https://code.google.com/p/svgweb/issues/detail?id=591): Round coordinates in mouse event
  * [Issue 594](https://code.google.com/p/svgweb/issues/detail?id=594): Excessive resizing of flash - prior to load of content
  * [Issue 596](https://code.google.com/p/svgweb/issues/detail?id=596): adjacent Rectangles lead to striped artifacts (Flash renderer) (regression from [Issue 514](https://code.google.com/p/svgweb/issues/detail?id=514),[r1209](https://code.google.com/p/svgweb/source/detail?r=1209))
  * [Issue 360](https://code.google.com/p/svgweb/issues/detail?id=360): Rewrite examples and docs to do object detection for SVG Web so it can be later removed
  * [Issue 273](https://code.google.com/p/svgweb/issues/detail?id=273): Make browser unit tests that specify Standards Compliant Doctype/HTML 5 Doctype at the top
  * [Issue 573](https://code.google.com/p/svgweb/issues/detail?id=573): Support IE 9
  * [Issue 597](https://code.google.com/p/svgweb/issues/detail?id=597): removeEventListener not working fully; Two slider instances should behave independently
  * [Issue 599](https://code.google.com/p/svgweb/issues/detail?id=599): onsvgload event not fired on Opera native mode with clear cache
  * [Issue 357](https://code.google.com/p/svgweb/issues/detail?id=357): Enhancement: Replace demo viewBox manipulation with true zoom and pan
  * [Issue 427](https://code.google.com/p/svgweb/issues/detail?id=427): Setting size of the root element does not cause the flash object to resize

## svgweb-2010-08-30-Owlephant.zip ([r1232](https://code.google.com/p/svgweb/source/detail?r=1232)) ##
  * [Issue 471](https://code.google.com/p/svgweb/issues/detail?id=471): Radial gradient different between Flash and Native renders
  * [Issue 349](https://code.google.com/p/svgweb/issues/detail?id=349): gradients with bounding box cooordinates are positioned wrongly on circles
  * [Issue 475](https://code.google.com/p/svgweb/issues/detail?id=475): 'this' not getting set correctly in SVG element event callback
  * [Issue 477](https://code.google.com/p/svgweb/issues/detail?id=477): The change in the size of the ClipPath area is not reflected by Flash Renderer.
  * [Issue 483](https://code.google.com/p/svgweb/issues/detail?id=483): Changing gradient stop does not trigger redraw of referencing elements
  * [Issue 484](https://code.google.com/p/svgweb/issues/detail?id=484): Dynamic clip-path attribute changes are not reflected.
  * [Issue 476](https://code.google.com/p/svgweb/issues/detail?id=476): `<set>` Element Problems and numerous SMIL issues
  * [Issue 489](https://code.google.com/p/svgweb/issues/detail?id=489): Support beginElement() for animation elements
  * [Issue 494](https://code.google.com/p/svgweb/issues/detail?id=494): SVGTextNode.onDrawGlyph not removing glyph clones
  * [Issue 495](https://code.google.com/p/svgweb/issues/detail?id=495): Support units-per-em on SVG fonts
  * [Issue 492](https://code.google.com/p/svgweb/issues/detail?id=492): 'button' property missing in mouse event object
  * [Issue 472](https://code.google.com/p/svgweb/issues/detail?id=472): get svg.js even more compressed with Google's closure compiler (30K reduction)
  * [Issue 499](https://code.google.com/p/svgweb/issues/detail?id=499): Object loaded svg with scripts not firing window load or SVGLoad event
  * [Issue 488](https://code.google.com/p/svgweb/issues/detail?id=488): Updating styles via Javascript does not visibly update child nodes in IE/Flash
  * [Issue 496](https://code.google.com/p/svgweb/issues/detail?id=496): Support exponents in path values
  * [Issue 502](https://code.google.com/p/svgweb/issues/detail?id=502): Radial Gradient userSpaceOnUse Matrix calculated incorrectly
  * [Issue 503](https://code.google.com/p/svgweb/issues/detail?id=503): Radial Gradient focalLen not used for stroke
  * [Issue 504](https://code.google.com/p/svgweb/issues/detail?id=504): Radial Gradient userSpaceOnUse Matrix calculated incorrectly for SVGCircle and SVGEllipse nodes
  * [Issue 497](https://code.google.com/p/svgweb/issues/detail?id=497): bad 'target' when click on text node
  * [Issue 342](https://code.google.com/p/svgweb/issues/detail?id=342): Event handler fires only after second mouse click.
  * [Issue 507](https://code.google.com/p/svgweb/issues/detail?id=507): Namespaced elements not allowed until svg element added to page
  * [Issue 158](https://code.google.com/p/svgweb/issues/detail?id=158): Rotated text not rendering for native fonts (Mostly Fixed)
  * [Issue 467](https://code.google.com/p/svgweb/issues/detail?id=467): Namespace exception loading video example in IE8
  * [Issue 510](https://code.google.com/p/svgweb/issues/detail?id=510): Font Family not used when surrounded by single quotes in Flash 10.1
  * [Issue 57](https://code.google.com/p/svgweb/issues/detail?id=57): SVG default fill-rule 'nonzero' not supported by flash 9
  * [Issue 123](https://code.google.com/p/svgweb/issues/detail?id=123): Nested `<svg>` elements don't show up in the DOM correctly
  * [Issue 145](https://code.google.com/p/svgweb/issues/detail?id=145): dynamically creating SMIL elements and attributes
  * [Issue 356](https://code.google.com/p/svgweb/issues/detail?id=356): Show SVG Web Release Name and Revision in Right Click Menu
  * [Issue 513](https://code.google.com/p/svgweb/issues/detail?id=513): getElementsByTagNameNS returning text nodes
  * [Issue 515](https://code.google.com/p/svgweb/issues/detail?id=515): Call handleEvent on EventListener objects passed to addEventListener
  * [Issue 517](https://code.google.com/p/svgweb/issues/detail?id=517): Elements with fill set to 'none' should produce mouse events but do not
  * [Issue 518](https://code.google.com/p/svgweb/issues/detail?id=518): Avoid redraw on change to pointer-events attribute
  * [Issue 523](https://code.google.com/p/svgweb/issues/detail?id=523): Event listener from object element may be applied to svg element erroneously
  * [Issue 522](https://code.google.com/p/svgweb/issues/detail?id=522): Need way to create element with self declared namespace
  * [Issue 525](https://code.google.com/p/svgweb/issues/detail?id=525): Image element not respecting display='none'
  * [Issue 524](https://code.google.com/p/svgweb/issues/detail?id=524): Jquery $(window).scroll event will not fire
  * [Issue 527](https://code.google.com/p/svgweb/issues/detail?id=527): Excessive messages for detached event listeners
  * [Issue 528](https://code.google.com/p/svgweb/issues/detail?id=528): Exception if remove event listener from detached element, then add to document
  * [Issue 321](https://code.google.com/p/svgweb/issues/detail?id=321): Support for animating path 'd' attribute (and interpolate between values)
  * [Issue 514](https://code.google.com/p/svgweb/issues/detail?id=514): clip-path not used when part of style attribute value
  * [Issue 526](https://code.google.com/p/svgweb/issues/detail?id=526): Object using clip path cannot have its opacity animated
  * [Issue 535](https://code.google.com/p/svgweb/issues/detail?id=535): Nested svg disappears when animated
  * [Issue 536](https://code.google.com/p/svgweb/issues/detail?id=536): Problems tracking whether elements attached to document or not
  * [Issue 537](https://code.google.com/p/svgweb/issues/detail?id=537): Animation added in onload listener does not initialize
  * [Issue 538](https://code.google.com/p/svgweb/issues/detail?id=538): Node removed while invalid causes endless frame listening
  * [Issue 539](https://code.google.com/p/svgweb/issues/detail?id=539): Animation with invalid or forward href causes exception
  * [Issue 540](https://code.google.com/p/svgweb/issues/detail?id=540): script stack space quota is exhausted by large svg file
  * [Issue 511](https://code.google.com/p/svgweb/issues/detail?id=511): Keyboard events are not supported properly

## svgweb-2010-04-09-Dracolisk.zip ([r1115](https://code.google.com/p/svgweb/source/detail?r=1115)) ##
  * [Issue 378](https://code.google.com/p/svgweb/issues/detail?id=378): Undefined variable in svg.js source code
  * [Issue 435](https://code.google.com/p/svgweb/issues/detail?id=435): Regression: test\_js1.html and test\_js2.html fail
  * [Issue 421](https://code.google.com/p/svgweb/issues/detail?id=421): Reuse XML ActiveX object on Internet Explorer
  * [Issue 431](https://code.google.com/p/svgweb/issues/detail?id=431): unsuspendRedrawAll not wired to several methods
  * [Issue 428](https://code.google.com/p/svgweb/issues/detail?id=428): setAttribute gives error for undefined or null attribute value (Flash renderer)
  * [Issue 264](https://code.google.com/p/svgweb/issues/detail?id=264): Text with fractional font-size not displayed
  * [Issue 405](https://code.google.com/p/svgweb/issues/detail?id=405): Support x,y lists on tspan for positioning native font glyphs
  * [Issue 440](https://code.google.com/p/svgweb/issues/detail?id=440): Text with large font-size displays smaller
  * [Issue 447](https://code.google.com/p/svgweb/issues/detail?id=447): Text placement changes with different viewboxes
  * [Issue 296](https://code.google.com/p/svgweb/issues/detail?id=296): appendChild of existing child should move it to the end
  * [Issue 462](https://code.google.com/p/svgweb/issues/detail?id=462): clipPath outside of def tag renders and blacks out the image
  * [Issue 415](https://code.google.com/p/svgweb/issues/detail?id=415): Dynamic change of HREF on `<use>` to different local definition does not work (setAttributeNS())
  * [Issue 456](https://code.google.com/p/svgweb/issues/detail?id=456): xlink:href attribute on images does not properly change with the Flash renderer
  * [Issue 460](https://code.google.com/p/svgweb/issues/detail?id=460): Event type is not passed through when mouse events are raised.
  * [Issue 465](https://code.google.com/p/svgweb/issues/detail?id=465): Stretched images have no smoothing
  * [Issue 375](https://code.google.com/p/svgweb/issues/detail?id=375): Problem with using svgweb and jquery together
  * [Issue 402](https://code.google.com/p/svgweb/issues/detail?id=402): Make sure SVG Web and Mootools work together
  * [Issue 403](https://code.google.com/p/svgweb/issues/detail?id=403): Make sure SVG Web and Prototype.js work together
  * [Issue 404](https://code.google.com/p/svgweb/issues/detail?id=404): Make sure SVG Web and Ext.js work together
  * [Issue 438](https://code.google.com/p/svgweb/issues/detail?id=438): Support SVG '`RenderingProperties`' CSS Values for Performance Vs. Quality Tradeoffs
  * [Issue 437](https://code.google.com/p/svgweb/issues/detail?id=437): Slow rendering with mitered corners
  * [Issue 452](https://code.google.com/p/svgweb/issues/detail?id=452): Parsing complicated long path statements extremely slow
  * [Issue 251](https://code.google.com/p/svgweb/issues/detail?id=251): data-path configuration via meta tag
  * [Issue 332](https://code.google.com/p/svgweb/issues/detail?id=332): Formally move to not supporting re-namespacing SVG elements
  * [Issue 468](https://code.google.com/p/svgweb/issues/detail?id=468): SVG Image regression in test\_browser1.html
  * [Issue 287](https://code.google.com/p/svgweb/issues/detail?id=287): Get large SVG file with lots of PATH nodes where PATH node data has lots of new lines in it faster
  * [Issue 466](https://code.google.com/p/svgweb/issues/detail?id=466): Semi-legal regex is used in the code.
  * [Issue 424](https://code.google.com/p/svgweb/issues/detail?id=424): `getElementsByTagNameNS(svgns, 'svg')[0]` fails in IE7
  * [Issue 111](https://code.google.com/p/svgweb/issues/detail?id=111): Implement removeEventListener
  * [Issue 354](https://code.google.com/p/svgweb/issues/detail?id=354): Speed up rxt360's mapping example
  * [Issue 409](https://code.google.com/p/svgweb/issues/detail?id=409): `CurrentScale` does not function properly for dynamically created SVG
  * [Issue 445](https://code.google.com/p/svgweb/issues/detail?id=445): Scripted SVG File Causes Stack Overflow in svgweb
  * [Issue 217](https://code.google.com/p/svgweb/issues/detail?id=217): replaceChild + setAttribute can lead to display glitches for Flash viewer
  * [Issue 181](https://code.google.com/p/svgweb/issues/detail?id=181): insertBefore adds object twice which can cause strange display errors

## svgweb-2009-11-23-Gelatinous-Cube.zip ([r998](https://code.google.com/p/svgweb/source/detail?r=998)) ##
  * [Issue 358](https://code.google.com/p/svgweb/issues/detail?id=358): Opera throws exception on patch to currentTranslate
  * [Issue 413](https://code.google.com/p/svgweb/issues/detail?id=413): Implement node.getElementsByTagNameNS scoped by container node
  * [Issue 401](https://code.google.com/p/svgweb/issues/detail?id=401): currentTranslate.setXY does translate the svg, but doesn't affect currentTranslate.getX or getY
  * [Issue 201](https://code.google.com/p/svgweb/issues/detail?id=201): Support cloneNode
  * [Issue 385](https://code.google.com/p/svgweb/issues/detail?id=385): Implement getAttributeNS
  * [Issue 384](https://code.google.com/p/svgweb/issues/detail?id=384): Make sure ownerDocument defaults to 'document'
  * [Issue 386](https://code.google.com/p/svgweb/issues/detail?id=386): Implement hasAttributeNS and hasAttribute
  * [Issue 387](https://code.google.com/p/svgweb/issues/detail?id=387): Implement removeAttributeNS and removeAttribute
  * [Issue 202](https://code.google.com/p/svgweb/issues/detail?id=202): Programmatically Creating the SVG node
  * [Issue 383](https://code.google.com/p/svgweb/issues/detail?id=383): QA on Firefox 3.6 Beta
  * [Issue 335](https://code.google.com/p/svgweb/issues/detail?id=335): Specific SVG file crashes browser when used with SVG Web
  * [Issue 364](https://code.google.com/p/svgweb/issues/detail?id=364): onload event does not fire when image url is a security error
  * [Issue 362](https://code.google.com/p/svgweb/issues/detail?id=362): dynamically applied color should cascade
  * [Issue 349](https://code.google.com/p/svgweb/issues/detail?id=349): gradients with bounding box cooordinates are positioned wrongly on circles
  * [Issue 371](https://code.google.com/p/svgweb/issues/detail?id=371): Linear gradients incorrectly start at left of screen rather than each circle
  * [Issue 367](https://code.google.com/p/svgweb/issues/detail?id=367): Flash blend mode used for groups is a performance problem and can be avoided generally
  * [Issue 331](https://code.google.com/p/svgweb/issues/detail?id=331): Animations based on events not implemented; problems with transform animations
  * [Issue 275](https://code.google.com/p/svgweb/issues/detail?id=275): Add View Dynamic Source to context menu
  * [Issue 297](https://code.google.com/p/svgweb/issues/detail?id=297): Aspect resolution of viewBox not honored on resize of browser
  * [Issue 238](https://code.google.com/p/svgweb/issues/detail?id=238): SVGImageNode.as should absorb exceptions due to invalid image URL
  * [Issue 337](https://code.google.com/p/svgweb/issues/detail?id=337): https generates insecure warning with IE6 (FIXED for IE7 and IE8)
  * [Issue 388](https://code.google.com/p/svgweb/issues/detail?id=388): Cannot Add USE elements dynamically
  * [Issue 361](https://code.google.com/p/svgweb/issues/detail?id=361): Text label is stealing mouse click

## svgweb-2009-10-12-Beholder.zip ([r924](https://code.google.com/p/svgweb/source/detail?r=924)) ##
  * [Issue 327](https://code.google.com/p/svgweb/issues/detail?id=327): Patching currentTranslate in causes error in Wikipedia Pan and Zoom tool
  * [Issue 326](https://code.google.com/p/svgweb/issues/detail?id=326): Update config.html tool to test for SVG MIME type
  * [Issue 316](https://code.google.com/p/svgweb/issues/detail?id=316): Background SVG is not being re-drawn on secondary pages for some browsers
  * [Issue 307](https://code.google.com/p/svgweb/issues/detail?id=307): Window resize handler can sometimes throw exceptions on IE if Flash not ready
  * [Issue 308](https://code.google.com/p/svgweb/issues/detail?id=308): Implement currentTranslate and currentScale and have it be a fast path
  * [Issue 312](https://code.google.com/p/svgweb/issues/detail?id=312): For Shelley Powers: Odd error when using within XHTML document: works with Firefox, does not work with any other browser
  * [Issue 176](https://code.google.com/p/svgweb/issues/detail?id=176): Document Makefile dependencies
  * [Issue 233](https://code.google.com/p/svgweb/issues/detail?id=233): (regression) inconsistent size, spacing, flow of rendering
  * [Issue 304](https://code.google.com/p/svgweb/issues/detail?id=304): tspan-tag ignore s coordinates of upper text-tag
  * [Issue 305](https://code.google.com/p/svgweb/issues/detail?id=305): Changing shapes and paths from 'hidden' to 'visible' does not work.
  * [Issue 306](https://code.google.com/p/svgweb/issues/detail?id=306): Regression in test\_js1.html: Text that should be hidden is not
  * [Issue 311](https://code.google.com/p/svgweb/issues/detail?id=311): Summation of transform causes shaking and invalid transformations.
  * [Issue 254](https://code.google.com/p/svgweb/issues/detail?id=254): Lamb Animation Sample Doesn't Look Correct
  * [Issue 315](https://code.google.com/p/svgweb/issues/detail?id=315): Reduce the number of Sprites created per Node to increase performance
  * [Issue 321](https://code.google.com/p/svgweb/issues/detail?id=321): Support for animating path "d" attribute (except interpolation)
  * [Issue 325](https://code.google.com/p/svgweb/issues/detail?id=325): Support data: URL scheme for object tag
  * [Issue 329](https://code.google.com/p/svgweb/issues/detail?id=329): in flash renderer, images get cropped if they are moved programmatically
  * [Issue 330](https://code.google.com/p/svgweb/issues/detail?id=330): in flash renderer, fill with image pattern does not work (programmatically)
  * [Issue 293](https://code.google.com/p/svgweb/issues/detail?id=293): Position of image differs in native vs flash
  * [Issue 207](https://code.google.com/p/svgweb/issues/detail?id=207): Doing transform on image dynamically throws exception
  * [Issue 343](https://code.google.com/p/svgweb/issues/detail?id=343): Support on`*` events in SVG "use" element.
  * [Issue 344](https://code.google.com/p/svgweb/issues/detail?id=344): Cache image requests for same file

## svgweb-2009-09-16-Umberhulk-B.zip ([r857](https://code.google.com/p/svgweb/source/detail?r=857)) ##
Release Name: [Umber Hulk](http://codinginparadise.org/monsters/umberhulk.jpg) - "A human-shaped creature with gaping maws flanked by pairs of exceedingly sharp mandibles. Despite their bestial appearance, umber hulks possess a significant intelligence and language of their own."

  * [Issue 299](https://code.google.com/p/svgweb/issues/detail?id=299): Tip of subversion ([r855](https://code.google.com/p/svgweb/source/detail?r=855)) throws error for demo.html on IE 7
  * [Issue 292](https://code.google.com/p/svgweb/issues/detail?id=292): For Wikipedia: Fix SVG OBJECT creation bugs discovered
  * [Issue 285](https://code.google.com/p/svgweb/issues/detail?id=285): For Wikipedia: Be able to host bulk of SVG Web on a different domain
  * [Issue 271](https://code.google.com/p/svgweb/issues/detail?id=271): When using uncompressed-svg.js the data-path attribute on the script element is ignored
  * [Issue 140](https://code.google.com/p/svgweb/issues/detail?id=140): SVG OBJECT.contentDocument does not work when DOCTYPE specified inside of HTML file itself
  * [Issue 272](https://code.google.com/p/svgweb/issues/detail?id=272): Fetching contentDocument on SVG OBJECT does not work in IE 8/Standards Mode `[INVALID]`
  * [Issue 249](https://code.google.com/p/svgweb/issues/detail?id=249): flash renderer svgobj.contentDocument breaks if svg contains DOCTYPE declaration
  * [Issue 148](https://code.google.com/p/svgweb/issues/detail?id=148): QA in IE 8 with standards mode on
  * [Issue 186](https://code.google.com/p/svgweb/issues/detail?id=186): test\_js2.html has issues on some IE 8 instances with compatibility mode on
  * [Issue 135](https://code.google.com/p/svgweb/issues/detail?id=135): Help functionality on blocks\_game.html issue
  * [Issue 236](https://code.google.com/p/svgweb/issues/detail?id=236): wrong URL encoding for UTF-8 Chinese characters
  * [Issue 250](https://code.google.com/p/svgweb/issues/detail?id=250): svgweb init fails in internet explorer 8 when using object embedding
  * [Issue 260](https://code.google.com/p/svgweb/issues/detail?id=260): The full-color-prof-01-f.html in the test suite 1.1 is broken
  * [Issue 262](https://code.google.com/p/svgweb/issues/detail?id=262): Remove onWindowResize handlers when page unloaded and when object removed from page
  * [Issue 263](https://code.google.com/p/svgweb/issues/detail?id=263): Click on root svg element does not work in IE8
  * [Issue 276](https://code.google.com/p/svgweb/issues/detail?id=276): Fix resize issues with Shelley's Burning Bird site
  * [Issue 277](https://code.google.com/p/svgweb/issues/detail?id=277): Disappearing text
  * [Issue 279](https://code.google.com/p/svgweb/issues/detail?id=279): Define evt variable in onload="" handler script code
  * [Issue 283](https://code.google.com/p/svgweb/issues/detail?id=283): getScreenCTM needs to include object position and ignore browser zoom
  * [Issue 286](https://code.google.com/p/svgweb/issues/detail?id=286): 100% w/h SVG Root in 100% w/h Object in a DIV given in px – Flash size wrong
  * [Issue 290](https://code.google.com/p/svgweb/issues/detail?id=290): Referencing an "svg" object with "use" causes flash error
  * [Issue 294](https://code.google.com/p/svgweb/issues/detail?id=294): Support getCTM, currentScale, currentTranslate for drag and drop
  * [Issue 53](https://code.google.com/p/svgweb/issues/detail?id=53): Support on`*` style event handlers directly in markup `[for OBJECT tag only]`

## svgweb-2009-09-09-Owlbear.zip ([r798](https://code.google.com/p/svgweb/source/detail?r=798)) ##
Release Name: [Owlbear](http://codinginparadise.org/monsters/owlbear.jpg) - "Terrifying: the body of a bear... the head of an owl"

  * [Issue 268](https://code.google.com/p/svgweb/issues/detail?id=268): Unload errors on IE 6
  * [Issue 262](https://code.google.com/p/svgweb/issues/detail?id=262): Remove onWindowResize handlers when page unloaded and when object removed from page
  * [Issue 261](https://code.google.com/p/svgweb/issues/detail?id=261): HTC Nodes not removed when SVG Objects removed from the page
  * [Issue 134](https://code.google.com/p/svgweb/issues/detail?id=134): Fix demo.html glitches
  * [Issue 88](https://code.google.com/p/svgweb/issues/detail?id=88): View source from the flash context menu.
  * [Issue 242](https://code.google.com/p/svgweb/issues/detail?id=242): Tspans do not offset from their parent.
  * [Issue 225](https://code.google.com/p/svgweb/issues/detail?id=225): Implement getScreenCTM, matrix inversion, createSVGPoint, SVGPoint.matrixTransform.
  * [Issue 245](https://code.google.com/p/svgweb/issues/detail?id=245): Not working in Firefox 1.0 `[WONTFIX]`
  * [Issue 124](https://code.google.com/p/svgweb/issues/detail?id=124): Install and QA on Firefox 3.5
  * [Issue 131](https://code.google.com/p/svgweb/issues/detail?id=131): Copy uncompressed source files over during build process to aid debugging
  * [Issue 177](https://code.google.com/p/svgweb/issues/detail?id=177): Fix the javascript-samples/`*_`dynamic.html samples
  * [Issue 258](https://code.google.com/p/svgweb/issues/detail?id=258): Separate SWF from HTC
  * [Issue 229](https://code.google.com/p/svgweb/issues/detail?id=229): Speedup page load time of MichaelN's static map page on IE
  * [Issue 216](https://code.google.com/p/svgweb/issues/detail?id=216): Have svg.swf load up earlier in the page load process
  * [Issue 190](https://code.google.com/p/svgweb/issues/detail?id=190): Speed up age population sample
  * [Issue 257](https://code.google.com/p/svgweb/issues/detail?id=257): SVG files with no XML declaration should work
  * [Issue 104](https://code.google.com/p/svgweb/issues/detail?id=104): Purple Circle in Third SVG Image in Tests Not Transparent
  * [Issue 150](https://code.google.com/p/svgweb/issues/detail?id=150): Background rectangle not right size in photos.svg when using Flash Handler
  * [Issue 163](https://code.google.com/p/svgweb/issues/detail?id=163): Sizing of embedded SVG differs between Flash and Native when browser text zoom setting is different
  * [Issue 166](https://code.google.com/p/svgweb/issues/detail?id=166): percentage values for width/height in svgroot: map converted from shapefle doesn't display
  * [Issue 171](https://code.google.com/p/svgweb/issues/detail?id=171): Width and Height of 100% on SVG root node has display glitch on IE 7
  * [Issue 193](https://code.google.com/p/svgweb/issues/detail?id=193): SVG OBJECT in Wikipedia test page not scaled correctly with Flash renderer `[WONTFIX]`
  * [Issue 233](https://code.google.com/p/svgweb/issues/detail?id=233): inconsistent size, spacing, flow of rendering

## svgweb-2009-08-20.zip ([r746](https://code.google.com/p/svgweb/source/detail?r=746)) ##
  * [Issue 218](https://code.google.com/p/svgweb/issues/detail?id=218): The way SVG Web bootstraps directly embedded SVG in HTML into the page is very slow on FF/Native
  * [Issue 175](https://code.google.com/p/svgweb/issues/detail?id=175): Window.onload listener for Native handler doesn't fire for some situations when both embedded SVG and SVG OBJECTs on page
  * [Issue 219](https://code.google.com/p/svgweb/issues/detail?id=219): body.onload not fired for SVG OBJECT
  * [Issue 228](https://code.google.com/p/svgweb/issues/detail?id=228): onload attribute on an SVG root tag with direct embedded SVG does not fire
  * [Issue 215](https://code.google.com/p/svgweb/issues/detail?id=215): Implement DocumentFragment API
  * [Issue 223](https://code.google.com/p/svgweb/issues/detail?id=223): Remove `_`DOMException and `_`SVGException classes from JS
  * [Issue 206](https://code.google.com/p/svgweb/issues/detail?id=206): support booleans altKey, shiftKey, and ctrlKey on mouse event
  * [Issue 220](https://code.google.com/p/svgweb/issues/detail?id=220): Error in parsing Path data Z,z commands do not update current postion
  * [Issue 221](https://code.google.com/p/svgweb/issues/detail?id=221): DOCTYPE ENTITYs not expanded on certain browsers (safari,opera)

## svgweb-2009-08-11.zip ([r696](https://code.google.com/p/svgweb/source/detail?r=696)) ##
  * [Issue 110](https://code.google.com/p/svgweb/issues/detail?id=110): Implement suspendRedraw/unsuspendRedraw
  * [Issue 200](https://code.google.com/p/svgweb/issues/detail?id=200): Convert Flash communication to pass Strings instead of Objects
  * [Issue 194](https://code.google.com/p/svgweb/issues/detail?id=194): Missing height and width of `<svg>` element causes failure to render (flash/flex only)
  * [Issue 197](https://code.google.com/p/svgweb/issues/detail?id=197): pointer-events="none" is not respected when rendered with Flash
  * [Issue 188](https://code.google.com/p/svgweb/issues/detail?id=188): Support Mouse Click Event (using addEventListener)
  * [Issue 195](https://code.google.com/p/svgweb/issues/detail?id=195): addEventListener example: evt.target.id "undefined" in ie7 & ie8

## svgweb-2009-07-28.zip ([r650](https://code.google.com/p/svgweb/source/detail?r=650)) ##
  * [Issue 168](https://code.google.com/p/svgweb/issues/detail?id=168): "text-anchor jumps back and forth on dynamically changed text"
  * [Issue 141](https://code.google.com/p/svgweb/issues/detail?id=141): "Get our docs in order" ([Quick Start guide](http://codinginparadise.org/projects/svgweb/docs/QuickStart.html) and starting examples)
  * [Issue 187](https://code.google.com/p/svgweb/issues/detail?id=187): "firstChild, lastChild, nextSibling, and previousSibling not passing through changes to Flash for IE"
  * [Issue 183](https://code.google.com/p/svgweb/issues/detail?id=183): "getElementsByTagNameNS on IE has issues with certain versions of MSXML"
  * [Issue 114](https://code.google.com/p/svgweb/issues/detail?id=114): "Duplicate variable definition warnings, Missing type declarations"
  * [Issue 179](https://code.google.com/p/svgweb/issues/detail?id=179): "Errors when running demo"
  * [Issue 178](https://code.google.com/p/svgweb/issues/detail?id=178): "Element.style.`*` access doesn't work for Firefox Native under some conditions"
  * [Issue 182](https://code.google.com/p/svgweb/issues/detail?id=182): "Regression where unit test for getElementsByTagNameNS for SVG OBJECTs with Flash handler fails"
  * [Issue 180](https://code.google.com/p/svgweb/issues/detail?id=180): "SVG Spec defaults for overflow and display CSS properties incorrectly applied to OBJECT tags"
  * [Issue 128](https://code.google.com/p/svgweb/issues/detail?id=128): "Sprites created by SVGNode to solve certain issues not created in scripting scenario"
  * [Issue 174](https://code.google.com/p/svgweb/issues/detail?id=174): "Create a config.html file that helps with MIME settings"
  * [Issue 173](https://code.google.com/p/svgweb/issues/detail?id=173): "Make COMPRESS=0 the default in Makefile"
  * [Issue 164](https://code.google.com/p/svgweb/issues/detail?id=164): "Firefox gets scroll bars on SVG OBJECTs sometimes"
  * [Issue 159](https://code.google.com/p/svgweb/issues/detail?id=159): "Bundle a small web server (Jetty) to make getting started quicker"
  * [Issue 157](https://code.google.com/p/svgweb/issues/detail?id=157): "Create utility files (PHP, ASP, JSP) for those in situations where they can't set MIME type"
  * [Issue 113](https://code.google.com/p/svgweb/issues/detail?id=113): "null check for _xml in_getAttribute"