---
title: Tessellate: Recreating the Demo - The Team Page
description: Your Guide to Recreating Elements of the Tessellate Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/tessellate:Tessellate

---

Introduction
-----

**The Team** example page demonstrates how you can create a rich team page with the Tessellate template. Here is some information to help you replicate this page as it appears in the demo.

Menu Item Options
-----

![][theteampage2]

**The Team** page is a **Single Article** menu item type. To recreate the layout the way it appears in our demo, enter `the-team` in the **Alias** field in the menu item settings. This alias is tied to a class in the demo.less file.

In order for this to work, you should have the **Page Suffix** option set to **On** in **Administrator > Template Manager > Template > Advanced**.

Mainbody
-----

![][theteampage6]

The page's content body is set in the **The Team** article. You will find the content used in the article below.

~~~ .html
<h3>Our Passion for Design</h3>
<p>Interactively procrastinate high-payoff content without backward-compatible data. Quickly cultivate optimal processes and tactical architectures. Completely iterate covalent strategic theme areas via accurate e-markets.</p>
<p>Completely synergize resource sucking relationships via premier niche markets. Professionally cultivate one-to-one customer service with robust ideas. Dynamically innovate resource-leveling customer service for state of the art customer service.</p>
<p><a href="http://www.rockettheme.com/joomla/templates/tessellate" class="readon">Learn More</a></p>
~~~

Modules
-----

Below is a brief rundown of the modules used to make up the demo page.

![][theteampage]

:   1. **RokAjaxSearch** [5%, 27%, se]
    1. **Custom HTML - The Team** [9%, 43%, se]
    3. **Breadcrumbs** [15%, 14%, se]
    4. **Article Content** [18%, 14%, se]
    5. **Custom HTML - Management Team** [26%, 13%, se]
    6. **Custom HTML - Core Developers** [52%, 13%, se]
    7. **Custom HTML - Support Assistants** [65%, 13%, se]
    8. **Custom HTML - We Are Hiring** [77%, 40%, se]
    9. **Custom HTML - Tessellate Demo** [82%, 13%, se]
    10. **Custom HTML - Sample Contact Info** [82%, 51%, se]
    11. **Menu - Copyright Menu** [92%, 72%, se]

1. [RokAjaxSearch](theteam.md#rokajaxsearch)
2. [Custom HTML - The Team](theteam.md#custom-html---the-team)
3. [Breadcrumbs](theteam.md#breadcrumbs)
4. [Article Content](theteam.md#mainbody)
5. [Custom HTML - Management Team](theteam.md#custom-html---management-team)
6. [Custom HTML - Core Developers](theteam.md#custom-html---core-developers)
7. [Custom HTML - Support Assistants](theteam.md#custom-html---support-assistants)
8. [Custom HTML - We Are Hiring](theteam.md#custom-html---we-are-hiring)
9. [Custom HTML - Tessellate Demo](theteam.md#custom-html---tessellate-demo)
10. [Custom HTML - Sample Contact Info](theteam.md#custom-html---sample-contact-info)
11. [Menu - Copyright Menu](theteam.md#menu---copyright-menu)


### RokAjaxSearch

![][theteampage3]

#### Details

| Option      | Setting            |
| :---------- | :----------        |
| Title       | `FP RokAjaxSearch` |
| Show Title  | Hide               |
| Position    | header-b           |
| Status      | Published          |
| Access      | Public             |

#### Module

| Option                            | Setting                                                  |
| :----------                       | :----------                                              |
| Search Page URL                   | `index.php?option=com_search&view=search&tmpl=component` |
| Advanced Search Page URL          | `index.php?option=com_search&view=search`                |
| Include RokAjaxSearch default CSS | No                                                       |
| Theme Style                       | Blue                                                     |
| Searchphrase                      | Any words                                                |
| Ordering                          | Newest First                                             |
| Limit                             | 10                                                       |
| Results Per Page                  | 3                                                        |
| Google Web Search                 | No                                                       |
| Google Blog Search                | No                                                       |
| Google Images Search              | No                                                       |
| Google Videos Search              | No                                                       |
| Show Pagination                   | Yes                                                      |
| Google SafeSearch                 | Moderate                                                 |
| Image Size to Search              | Medium                                                   |
| Show Estimated                    | Yes                                                      |
| Hide div id(s)                    | Blank                                                    |
| Link to All Results               | Yes                                                      |
| Show Description                  | Yes                                                      |
| Include (Category/Section)        | Yes                                                      |
| Show Read More Link               | Yes                                                      |

#### Advanced

| Option              | Setting            |
| :----------         | :----------        |
| Module Class Suffix | `fp-rokajaxsearch` |

### Custom HTML - The Team

![][theteampage4]

#### Module

| Option      | Setting                                                                      |
| :---------- | :-----------                                                                 |
| Title       | `The Team[span class="rt-title-tag"]Meet the People Behind Tessellate[/span]` |
| Show Title  | Yes                                                                          |
| Position    | top-a                                                                        |
| Status      | Published                                                                    |
| Access      | Public                                                                       |

#### Content

~~~ .html
&nbsp;
~~~

#### Options

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background-Image | Blank       |

#### Advanced

| Option                    | Setting                                       |
| :----------               | :----------                                   |
| Module Class Suffix       | `rt-center rt-title-large rt-nomodulecontent` |

### Breadcrumbs

![][theteampage5]

#### Module 

| Option              | Setting       |
| :----------         | :-----------  |
| Title               | `Breadcrumbs` |
| Show You Are Here   | No            |
| Show Home           | Yes           |
| Text for Home Entry |               |
| Show Last           | Yes           |
| Text Separator      |               |
| Show Title          | Hide          |
| Status              | Published     |
| Access              | Public        |

##### Advanced

| Option              | Setting     |
| :----------         | :---------- |
| Module Class Suffix |             |

### Custom HTML - Management Team

![][theteampage7]

#### Module

| Option      | Setting           |
| :---------- | :-----------      |
| Title       | `Management Team` |
| Show Title  | Yes               |
| Position    | mainbottom-a      |
| Status      | Published         |
| Access      | Public            |

#### Content

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-container">
        <div class="gantry-width-33">
            <div class="gantry-width-spacer">
                <span class="rt-image"><img src="images/rocketlauncher/pages/the-team/img-01.jpg" alt="image" /></span>
            </div>
        </div>

        <div class="gantry-width-66">
            <div class="gantry-width-spacer">
                <h3 class="nomarginbottom">Robert Smith</h3>
                <h6 class="nomargintop">CEO of Tessellate</h6>
                <p>Globally incubate standards compliant channels before scalable benefits. Quickly disseminate superior deliverables whereas web-enabled applications. <span class="hidden-tablet">Quickly drive clicks-and-mortar catalysts for change before vertical architectures.</span></p>
                <p class="success hidden-tablet">Image attribution: <a href="http://www.flickr.com/photos/astragony/8260117875/sizes/l/">AMaze by Daniele Zedda.</a></p>
            </div>
        </div>
    </div>
</div>

<div class="clear"></div><br />

<div class="gantry-row">
    <div class="gantry-width-container">
        <div class="gantry-width-33">
            <div class="gantry-width-spacer">
                <span class="rt-image"><img src="images/rocketlauncher/pages/the-team/img-03.jpg" alt="image" /></span>
            </div>
        </div>

        <div class="gantry-width-66">
            <div class="gantry-width-spacer">
                <h3 class="nomarginbottom">Tayla Parker</h3>
                <h6 class="nomargintop">Accountant</h6>
                <p>Globally incubate standards compliant channels before scalable benefits. Quickly disseminate superior deliverables whereas web-enabled applications. <span class="hidden-tablet">Quickly drive clicks-and-mortar catalysts for change before vertical architectures.</span></p>
                <p class="success hidden-tablet">Image attribution: <a href="http://www.flickr.com/photos/johnonolan/5729506059/sizes/l/">Stare by JohnONolan.</a></p>
            </div>
        </div>
    </div>
</div>

<div class="clear"></div><br />

<div class="gantry-row">
    <div class="gantry-width-container">
        <div class="gantry-width-33">
            <div class="gantry-width-spacer">
                <span class="rt-image"><img src="images/rocketlauncher/pages/the-team/img-02.jpg" alt="image" /></span>
            </div>
        </div>

        <div class="gantry-width-66">
            <div class="gantry-width-spacer">
                <h3 class="nomarginbottom">Paul Valdez</h3>
                <h6 class="nomargintop">Administrator</h6>
                <p>Globally incubate standards compliant channels before scalable benefits. Quickly disseminate superior deliverables whereas web-enabled applications. <span class="hidden-tablet">Quickly drive clicks-and-mortar catalysts for change before vertical architectures.</span></p>
                <p class="success hidden-tablet">Image attribution: <a href="http://www.flickr.com/photos/astragony/4728211246/sizes/l/">Bamboo by Daniele Zedda.</a></p>
            </div>
        </div>
    </div>
</div>

<div class="clear"></div>
~~~

#### Options

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background-Image | Blank       |

#### Advanced

| Option              | Setting                           |
| :----------         | :----------                       |
| Module Class Suffix | `rt-title-center rt-phone-center` |

### Custom HTML - Core Developers

![][theteampage8]

#### Module

| Option      | Setting           |
| :---------- | :-----------      |
| Title       | `Core Developers` |
| Show Title  | Yes               |
| Position    | mainbottom-a      |
| Status      | Published         |
| Access      | Public            |

#### Content

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-container">
        <div class="gantry-width-25">
            <div class="gantry-width-spacer">
                <span class="rt-image with-attribution">
                    <img src="images/rocketlauncher/pages/the-team/img-04.jpg" alt="image" />
                    <span class="rt-image rt-attribution"><a href="http://www.flickr.com/photos/johnonolan/5378754404/sizes/l/">by JohnONolan</a></span>
                </span>
                <h3 class="nomarginbottom">Enrik Prifti</h3>
                <h6 class="nomargintop">Programmer</h6>
            </div>
        </div>

        <div class="gantry-width-25">
            <div class="gantry-width-spacer">
                <span class="rt-image with-attribution">
                    <img src="images/rocketlauncher/pages/the-team/img-05.jpg" alt="image" />
                    <span class="rt-image rt-attribution"><a href="http://www.flickr.com/photos/thomasleuthard/5807793226/sizes/l/">by Thomas Leuthard</a></span>
                </span>
                <h3 class="nomarginbottom">Laura Richards</h3>
                <h6 class="nomargintop">Designer</h6>
            </div>
        </div>

        <div class="gantry-width-25">
            <div class="gantry-width-spacer">
                <span class="rt-image with-attribution">
                    <img src="images/rocketlauncher/pages/the-team/img-06.jpg" alt="image" />
                    <span class="rt-image rt-attribution"><a href="http://www.flickr.com/photos/astragony/5959165576/sizes/l/">by Daniele Zedda</a></span>
                </span>
                <h3 class="nomarginbottom">Alex Ward</h3>
                <h6 class="nomargintop">Technical Lead</h6>
            </div>
        </div>

        <div class="gantry-width-25">
            <div class="gantry-width-spacer">
                <span class="rt-image with-attribution">
                    <img src="images/rocketlauncher/pages/the-team/img-07.jpg" alt="image" />
                    <span class="rt-image rt-attribution"><a href="http://www.flickr.com/photos/mr-h/4217144639/sizes/l/">by AllansBrain</a></span>
                </span>
                <h3 class="nomarginbottom">Nora Mirone</h3>
                <h6 class="nomargintop">QA Lead</h6>
            </div>
        </div>
    </div>
</div>

<div class="clear"></div>
~~~

#### Options

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background-Image | Blank       |

#### Advanced

| Option              | Setting     |
| :----------         | :---------- |
| Module Class Suffix | `rt-center` |

### Custom HTML - Support Assistants

![][theteampage9]

#### Module

| Option      | Setting              |
| :---------- | :-----------         |
| Title       | `Support Assistants` |
| Show Title  | Yes                  |
| Position    | mainbottom-a         |
| Status      | Published            |
| Access      | Public               |

#### Content

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-container">
        <div class="gantry-width-20">
            <div class="gantry-width-spacer">
                <span class="rt-image with-attribution">
                    <img src="images/rocketlauncher/pages/the-team/img-08.jpg" alt="image" />
                    <span class="rt-image rt-attribution"><a href="http://www.flickr.com/photos/carianoff/5327733275/sizes/l/">by carianoff</a></span>
                </span>
                <h3 class="nomarginbottom">John Jensen</h3>
                <h6 class="nomargintop">Email</h6>
            </div>
        </div>

        <div class="gantry-width-20">
            <div class="gantry-width-spacer">
                <span class="rt-image with-attribution">
                    <img src="images/rocketlauncher/pages/the-team/img-09.jpg" alt="image" />
                    <span class="rt-image rt-attribution"><a href="http://www.flickr.com/photos/carianoff/4070347417/sizes/l/">by carianoff</a></span>
                </span>
                <h3 class="nomarginbottom">Tessa Page</h3>
                <h6 class="nomargintop">Ticket</h6>
            </div>
        </div>

        <div class="gantry-width-20">
            <div class="gantry-width-spacer">
                <span class="rt-image with-attribution">
                    <img src="images/rocketlauncher/pages/the-team/img-10.jpg" alt="image" />
                    <span class="rt-image rt-attribution"><a href="http://www.flickr.com/photos/carianoff/5328421868/sizes/l/">by carianoff</a></span>
                </span>
                <h3 class="nomarginbottom">Eric Timofti</h3>
                <h6 class="nomargintop">Chat</h6>
            </div>
        </div>

        <div class="gantry-width-20">
            <div class="gantry-width-spacer">
                <span class="rt-image with-attribution">
                    <img src="images/rocketlauncher/pages/the-team/img-11.jpg" alt="image" />
                    <span class="rt-image rt-attribution"><a href="http://www.flickr.com/photos/carianoff/5328368478/sizes/l/">by carianoff</a></span>
                </span>
                <h3 class="nomarginbottom">Lydia Back</h3>
                <h6 class="nomargintop">Facebook</h6>
            </div>
        </div>

        <div class="gantry-width-20">
            <div class="gantry-width-spacer">
                <span class="rt-image with-attribution">
                    <img src="images/rocketlauncher/pages/the-team/img-12.jpg" alt="image" />
                    <span class="rt-image rt-attribution"><a href="http://www.flickr.com/photos/carianoff/5327739397/sizes/l/">by carianoff</a></span>
                </span>
                <h3 class="nomarginbottom">Luca Coyle</h3>
                <h6 class="nomargintop">Twitter</h6>
            </div>
        </div>
    </div>
</div>

<div class="clear"></div>
~~~

#### Options

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background-Image | Blank       |

#### Advanced

| Option              | Setting     |
| :----------         | :---------- |
| Module Class Suffix | `rt-center` |

### Custom HTML - We are Hiring

![][theteampage10]

#### Module

| Option      | Setting         |
| :---------- | :-----------    |
| Title       | `We are Hiring` |
| Show Title  | Yes             |
| Position    | extension-a     |
| Status      | Published       |
| Access      | Public          |

#### Content

~~~ .html
<p>Join Our Awesome Team with a Great Work Environment</p>

<p><a href="http://www.rockettheme.com/joomla/templates/tessellate" class="readon largemargintop">Join Tessellate</a></p>
~~~

#### Options

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background-Image | Blank       |

#### Advanced

| Option              | Setting     |
| :----------         | :---------- |
| Module Class Suffix | `rt-center` |

### Custom HTML - Tessellate Demo

![][theteampage11]

#### Module

| Option      | Setting          |
| :---------- | :-----------     |
| Title       | `Tessellate Demo` |
| Show Title  | Yes              |
| Position    | footer-a         |
| Status      | Published        |
| Access      | Public           |

#### Content

~~~ .html
<p class="hidden-phone">These examples are intended to show how Tessellate can be constructed on your site, above and beyond the frontpage demonstration. These include Joomla content and component pages, with varying modular content, mainbody widths and page lengths.</p>
<p class="nomarginbottom">All demo content is for sample purpose only, intended to show a live site. Use the <a href="http://www.rockettheme.com/joomla/templates/tessellate">Tessellate RocketLauncher</a> to install an equivalent of the demo onto your site.</p>
~~~

#### Options

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background-Image | Blank       |

#### Advanced

| Option              | Setting           |
| :----------         | :----------       |
| Module Class Suffix | `rt-phone-center` |

### Custom HTML - Sample Contact Info

![][theteampage12]

#### Module

| Option      | Setting               |
| :---------- | :-----------          |
| Title       | `Sample Contact Info` |
| Show Title  | Yes                   |
| Position    | footer-b              |
| Status      | Published             |
| Access      | Public                |

#### Content

~~~ .html
<p>Completely synergize resource sucking relationships via premier niche markets. Professionally cultivate one-to-one customer service with robust ideas.</p>

<div class="gantry-width-container">
	<div class="gantry-width-40">
		<div class="gantry-width-spacer">
			<img src="images/rocketlauncher/pages/pages-overview/logo.png" alt="image" />
		</div>	
	</div>

	<div class="gantry-width-60">
		<div class="gantry-width-spacer">
			<span class="rt-intro-text">+1(123)456-5555-555</span><br />
			<span>Tessellate Theme, LLC</span><br />
			<span>123 Joomla! Boulevard</span><br />
			<span>Seattle, WA 00000, USA</span><br />
			<span><a href="#">noreply@domain.com</a></span>
		</div>
	</div>
</div>
<div class="clear"></div>
~~~

#### Options

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background-Image | Blank       |

#### Advanced

| Option              | Setting           |
| :----------         | :----------       |
| Module Class Suffix | `rt-phone-center` |

### Menu - Copyright Menu

![][theteampage13]

### Details

| Option      | Setting             |
| :---------- | :----------         |
| Title       | `FP Copyright Memu` |
| Show Title  | Hide                |
| Position    | copyright-b         |
| Status      | Published           |
| Access      | Public              |

### Basic Options

| Option              | Setting        |
| :----------         | :----------    |
| Select Menu         | Copyright Menu |
| Base Item           | Current        |
| Start Level         | 1              |
| End Level           | All            |
| Show Sub-menu Items | Yes            |

### Advanced Options

| Option              | Setting        |
| :----------         | :----------    |
| Module Class Suffix | `rt-horizmenu` |

[theteampage]: assets/page_theteam.jpeg
[theteampage2]: assets/page_theteam_2.jpeg
[theteampage3]: assets/page_theteam_3.jpeg
[theteampage4]: assets/page_theteam_4.jpeg
[theteampage5]: assets/page_theteam_5.jpeg
[theteampage6]: assets/page_theteam_6.jpeg
[theteampage7]: assets/page_theteam_7.jpeg
[theteampage8]: assets/page_theteam_8.jpeg
[theteampage9]: assets/page_theteam_9.jpeg
[theteampage10]: assets/page_theteam_10.jpeg
[theteampage11]: assets/page_theteam_11.jpeg
[theteampage12]: assets/page_theteam_12.jpeg
[theteampage13]: assets/demo_21.jpeg
