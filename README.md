[NodeBB Comments for PencilBlue](http://pencilblue.org)
=====

##### Add NodeBB comments to your articles

Installation and Setup
-----

1. Clone the nodebb-comments-pencilblue repository into the plugins folder of your PencilBlue installation
  ```shell
  cd [pencilblue_directory]/plugins
  git clone https://github.com/theunknownartisthour/nodebb-comments-pencilblue.git
  ```

2. Install the nodebb-comments-pencilblue plugin through the manage plugins screen in the admin section (/admin/plugins).

3. Go to the nodebb-comments-pencilblue settings screen (/admin/plugins/settings/nodebb-comments-pencilblue) and set your Disqus shortname.

4. Add the ```^tmp_nodebb_comments^``` directive in your article template where you want the comments to appear.

5. Add the ```^tmp_nodebb_comment_counts^``` directive at the bottom of pages where you want to display the comment counts for a list of articles.

*** Note *** Comment counts are not supported on external pages yet....

Code based on [https://github.com/pencilblue/disqus-pencilblue](https://github.com/pencilblue/disqus-pencilblue)
