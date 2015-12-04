<!--
{
"name" : "theming_content",
"version" : "0.1",
"title" : "Theming content",
"description" : "Drupal 8 Theming, Part 4",
"homepage" : "https://www.youtube.com/playlist?list=PLUBR53Dw-Ef818EUxzNoWKcQ7PYUXpFFA",
"freshnessDate" : 2015-12-04,
"license" : "Standard YouTube License"
}
-->

<!-- @section, "title" : "Part 09 - Introduction to Views" -->
		
<!-- @asset, "contentType": "outlearn/video", "provider": "youtube", "url": "https://www.youtube.com/watch?v=Ngm1jBVmqzk" -->
		
In this Drupal 8 Theming tutorial we are going to create dummy content using Devel module and display it on our front page using Views.
Views is one of the most powerful features of Drupal. It allows us to create custom queries on our content and display it on our pages or blocks.
In this episode we are first going to create dummy content using Devel module and then we are going to display it on our front page using Views.
And I can tell you right away, we are not going to like how that looks so we are going turn to Views once again and with a bit of help from css display our content just the way we like it :).
Devel module:
https://www.drupal.org/project/devel
Code used in this tutorial:
https://github.com/ivandoric/d8theming/releases/tag/9
http://watch-learn.com/video-tutorials/drupal-8-theming-part-09-introduction-to-views/
		
<!-- @section, "title" : "Part 10 - Creating and Displaying Content Types and Fields" -->
		
<!-- @asset, "contentType": "outlearn/video", "provider": "youtube", "url": "https://www.youtube.com/watch?v=f-cJfwUOGMg" -->

In this Drupal 8 Theming tutorial we are going to be talking about Content Types and Fields, one more powerful Drupal feature.
Content Types are just that, types of content that you can use to better manage data on your site. Something like Custom Post Types for WordPress, but they come out of the box with Drupal.
Content types usually consist of **Fields**. You can create very complicated types of data by using these two features. In this tutorial I'm going to show you how to create content type for inputing movies, with data like director, actors and movie poster.
Also we are going to use Devel module once again to generate content for this new content type.
http://watch-learn.com/video-tutorials/drupal-8-theming-part-10-creating-and-displaying-content-types-and-fields/

<!-- @section, "title" : "Part 11 - Displaying Fields" -->
		
<!-- @asset, "contentType": "outlearn/video", "provider": "youtube", "url": "https://www.youtube.com/watch?v=fQ6Ypik_jsE" -->
		
In this Drupal 8 Theming tutorial we are going to learn how to display fields in our template files.
In the previous episode we learned how to display a list of content types using Views. And in this episode we are going to learn how to display fields from our content type in our node template.
Code used in this tutorial:
https://github.com/ivandoric/d8theming/releases/tag/11
http://watch-learn.com/video-tutorials/drupal-8-theming-part-11-displaying-fields/
		
<!-- @section, "title" : "Part 12 - Images and Image Sizes " -->
		
<!-- @asset, "contentType": "outlearn/video", "provider": "youtube", "url": "https://www.youtube.com/watch?v=Hz9vTfV-a2I" -->

In this episode of Drupal 8 Theming tutorial series we are going to display image on our node, views and also learn how to make different image sizes for that image.
Drupal has a great functionality called Image Styles it's basically a way for you to define different image sizes and effects for your images. It can do everything from scaling and cropping to desaturating and rotating your images. Which is pretty cool in my opinion.
So in this tutorial we are going to add an image to our node template and resize it via image styles. Also we are going to add a different version of that image to our movies list using Views.
Code used in this tutorial:
https://github.com/ivandoric/d8theming/releases/tag/12
http://watch-learn.com/video-tutorials/drupal-8-theming-part-12-images-and-image-sizes/

<!-- @section, "title" : "Part 13 - Kint, Arrays, Twig, Foreach, If" -->
		
<!-- @asset, "contentType": "outlearn/video", "provider": "youtube", "url": "https://www.youtube.com/watch?v=-udFtu5LS0A" -->
		
In this episode of Drupal 8 Theming I'm going to show you a lot of stuff - how to work with Kint, how to print out data, how to make if statements with Twig and much more.
Kint is a debugger tool for Drupal, with it we can inspect all the data that is coming to our node, page, block or any other other type of content. With it we can see how we can accesses data that is coming to us from Drupal.
Of course, when we can see our data, we can then manipulate it. In this video I will show you how you can display values from your fields by using **foreach** loop, and also how you can prevent something from being displayed depending on user input.
Code used in this tutorial:
https://github.com/ivandoric/d8theming/releases/tag/13
http://watch-learn.com/video-tutorials/drupal-8-theming-part-13-kint-arrays-twig-foreach-if/
		
<!-- @section, "title" : "Part 14 - Field Collections" -->
		
<!-- @asset, "contentType": "outlearn/video", "provider": "youtube", "url": "https://www.youtube.com/watch?v=r7IxHD8aIMI" -->
		
In this tutorial of Drupal 8 Theming series we are going to do field collections. That means that we are going to group few fields together and display them in our theme.
For this we are going to use a module called, wait for it... Field Collection. That's right, the module is called by exactly what it does. And what it does is that it gives us a very easy way to make groups of fields that we can display on our node.
Field Collection:
https://www.drupal.org/project/field_collection
Code used in this video:
https://github.com/ivandoric/d8theming/releases/tag/14
http://watch-learn.com/video-tutorials/drupal-8-theming-part-14-field-collections/
		
<!-- @section, "title" : "Part 15 - Reference Fields" -->
		
<!-- @asset, "contentType": "outlearn/video", "provider": "youtube", "url": "https://www.youtube.com/watch?v=rnHEnw3ANpg" -->

In this episode of Drupal 8 Theming tutorials we are going to see how we can connect content on our site by using Reference Fields.
In this episode we are going to try and copy part of the IMDB sites functionality, where every movie has actors and those actors have their own pages with the information about them. So we are going to create a relationship between movies and actors that are in that movie.
All of this can be accomplished by using Reference Fields, and you will see exactly how in this video tutorial.
http://watch-learn.com/video-tutorials/drupal-8-theming-part-15-reference-fields/