## SoundCloud Audio

Embed a [SoundCloud](http://soundcloud.com) audio clip.

#### Syntax

{% raw %}
```
{% soundcloud clipID [color] %}
```
{% endraw %}

#### Required Parameters

- **clipID**
  Finding the audio clip's ID  can be kind of tricky. Go to the clip's SoundCloud page, click the Share button, switch over to the Embed tab, and then search through the embed code for a piece of text that looks similar to `api.soundcloud.com/tracks/152931962`. The string of numbers at the end `152931962` is the ID.

#### Optional Parameters

- **color** | Example: `0066CC`
  You can choose the color of the audio player. Use standard color hex values. You can use a color picker like [this one](http://www.rapidtables.com/web/color/color-picker.htm) to find the value you want.

#### Examples

{% raw %}
```
{% soundcloud 152931962 %}
```
{% endraw %}

{% raw %}
```
{% soundcloud 152931962 0066CC %}
```
{% endraw %}
