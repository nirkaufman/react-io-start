# The media player

- Link to video element docs: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/video

### Exercise

Please follow the instructor instructions!
Do not jump to part II if you are not asked.

#### Part I
1. Build a `VideoPlayer` component accept `src` as props.
2. The `VideoPlayer` component should support Play and Stop function (you can use the html snippets)

#### Part II
We should be able to control the appearance and location of the buttons
1. Think of the best way to support adding buttons from the `outside`
2. Break the feature to 3 seperated components:
   1. The `VideoPlayer` - plays the video
   2. The `Play` button component - when clicked: plays the video
   3. The `Pause` button component - when clicked: stops the video
   
__example:__
```html
<VideoPlayer src="" />
<Play onClick="play"/>
<Stop onClick="Pause" />
```

#### Part III
We should be able to choose any element that will operate as `Play` and `Stop` buttons.
1. Think of the best way to support custom `play` and `stop` buttons - with maximum flexibility
2. You can try to implement - or pseudocode - your idea if the time permits 


