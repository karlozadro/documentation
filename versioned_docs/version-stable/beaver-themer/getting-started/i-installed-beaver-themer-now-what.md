---
id: i-installed-beaver-themer-now-what
title: I installed Beaver Themer, now what?
sidebar_label: I installed Beaver Themer, now what?
---

Let's take a quick tour of Beaver Themer. If you're still not clear on where it works, there are examples plus screenshots [in this article](/beaver-themer/getting-started/what-can-i-do-with-beaver-themer.md).

## What can I build with Beaver Themer?

The Beaver Themer plugin is an add-on to the Beaver Builder plugin. Beaver Themer lets you use Beaver Builder to create layouts for the areas of a page or post that are normally controlled by the theme, plus a couple other layouts that you can't create directly in WordPress. This includes the following areas:

  * Headers and footers
  * Post title, post info, featured image, comments, sidebar (in other words, everything but post content) on single posts.
  * Index and archive pages that are generated by WordPress to list blog posts by date or by specific categories, tags, authors, etc.
  * The page displayed after a 404 error.
  * Parts of pages such as banners inserted into specific locations on the page, such as before the header, after the header, before the content.

For more information about theme-controlled areas, see the [primer on WordPress content and theme areas](/beaver-themer/getting-started/primer-on-wordpress-content-and-theme-areas-themer). For some screenshots and descriptions of Themer layouts, see the [Beaver Builder introductory article](/beaver-themer/getting-started/what-can-i-do-with-beaver-themer.md).

## Which themes support Beaver Themer?

See [this article](/beaver-themer/management-compatibility/beaver-themer-supported-themes.md) for which themes support Beaver Themer. If your theme isn't on the list, see whether you can [add code to make your theme support Header, Footer, and Part layouts](/beaver-themer/developer/add-header-footer-and-parts-support-to-your-theme-themer.md) in Beaver Themer.

## Where do I find Beaver Themer after I install it?

Beaver Themer has been integrated with the Beaver Builder plugin, and you'll see it mainly in two places in the UI, as described in the following sections.

### 1. Beaver Builder menu in the WordPress admin panel

There's a **Beaver Builder** admin panel nested in the WordPress admin panel, and when you install Beaver Themer, a new submenu appears called **Themer layouts**, as shown in the following screenshot.

![](/img/i-installed-beaver-themer-now-what-84e9b397.png)

:::tip **Tip**
Can't see **Beaver Builder** in your WordPress admin panel? See the article about [how to enable it](/beaver-builder/troubleshooting/miscellaneous/cant-find-the-beaver-builder-menu-in-the-admin-panel.md).
:::

### 2. Identify and edit Themer layouts from the WordPress admin bar

You'll also see Beaver Themer options in the WordPress admin bar at the top of the screen when you're logged in.

#### New menu

The **New** menu has a **Themer layout** selection, as shown in this screenshot.

![](/img/i-installed-beaver-themer-now-what-11c637e0.png)

#### Edit Themer Layout and Beaver Builder in the admin bar

When you're viewing a Themer layout, you'll see options to edit the Themer layout's settings or to open Beaver Builder to modify the Themer layout itself.

![](/img/i-installed-beaver-themer-now-what-c0fc0dc1.png)

If there's already a Beaver Builder layout on the page you're viewing, Beaver Builder will appear with a green dot next to it in the WordPress admin bar. If the dot is gray or white, it means there's currently no Beaver Builder layout.

If you're viewing a regular page and mouse over the Beaver Builder link, you'll see options to edit the page itself or any of the Themer layouts that apply to that page. ;For example, in the following screenshot you can choose to open either the page that you're viewing in Beaver Builder, or the Header-type Themer layout called "Sneak Peek home page," which is controlling the header on that page.

![](/img/i-installed-beaver-themer-now-what-bf74dcc9.png)

### 3. Field connections

When you open a module for editing in a Themer layout, you'll notice a plus sign next to some of the setting fields, as you can see in the following screenshot.

![](/img/i-installed-beaver-themer-now-what-34d69222.png)

These plus signs indicate that you can set [field connections](/beaver-themer/field-connections/field-connection-basics-themer.md) to eligible data from another area of your site. Field connections pull the content of the field from the particular page or post that's being displayed.

For example, the following screenshot shows part of a Singular Themer layout, in which the featured image is displayed as the row background, and the title, date, and author's name come  from the post that's being displayed, all by means of field connections. In other words, no matter which post the Themer layout appears on, it will display the content that's correct for that post.

![](/img/i-installed-beaver-themer-now-what-f3cdb7e1.jpg)

## Beaver Builder layouts in Beaver Themer vs. Post content area

As mentioned, Beaver Themer lets you create layouts that apply outside the content area of a page or post. In particular, Singular layouts apply to post titles, post info, the featured image, and so on, but not to the post content area.

:::important **Important**
If you apply Singular-type layouts for single posts, you can no longer use Beaver Builder to create layouts inside the post content area, and vice versa.
:::

For example, here's a single post viewed outside of Beaver Builder. In the WordPress admin bar you can see that the button following Beaver Builder is white, indicating that the post layout doesn't have a Beaver Builder layout. The submenu also indicates that there's a Header-type Themer layout and a Singular-type Themer layout applied to this page. If you click the Post to open this single post in Beaver Builder, you'll get a warning that if you do choose to open Beaver Builder to create a layout in the post content area, the Themer layout will no longer apply to this post.

![](/img/i-installed-beaver-themer-now-what-4073ffa6.jpg)

## Got it. What's next?

Try out [this quick tutorial on designing a Header layout](/beaver-themer/layout-types-modules/header-layout-type/tutorial-create-a-header-layout-themer.md).

Have a look at the layout types in Beaver Themer, their special modules, and where you can use them on your site:

* [Header](/beaver-themer/layout-types-modules/header-layout-type/themer-header-layout-type.md)
* [Footer](/beaver-themer/layout-types-modules/footer-layout-type/themer-footer-layout-type.md)
* [Archive](/beaver-themer/layout-types-modules/archive-layout-type/themer-archive-layout-type.md)
* [Singular](/beaver-themer/layout-types-modules/singular-layout-type/themer-singular-layout-type.md) (for single posts)
* [404](/beaver-themer/layout-types-modules/404-layout-type/themer-404-layout-type.md)
* [Part](/beaver-themer/layout-types-modules/part-layout-type/themer-part-layout-type.md)

Find out the power of using [field connections](/beaver-themer/field-connections/field-connection-basics-themer.md) and [field connection shortcodes](/beaver-themer/field-connections/field-connection-shortcodes-overview-themer.md), both in your Themer layouts and regular Beaver Builder layouts.

Use [conditional logic](/beaver-themer/conditional-logic/beaver-themer-conditional-logic.md) to fine-tune the locations where your Themer layouts appear.

Make use of custom post types and [custom fields](/beaver-themer/field-connections/connect-custom-fields-wordpress-toolset-pods-acf-themer.md) to take your website to the next level.

If you're a developer, have a look at the articles on how to customize [Themer modules](/beaver-themer/developer/customize-themer-modules.md) and [field connections](/beaver-themer/developer/customize-field-connections-themer.md).