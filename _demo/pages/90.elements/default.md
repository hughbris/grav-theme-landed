---
title: Elements
teaser: 'Ipsum dolor feugiat aliquam tempus sed magna lorem consequat accumsan'
# menu_classes: 'button primary EXAMPLE_ONLY'
process:
    twig: true
twig_first: true
---

<!-- Text -->
<section markdown="1">
### Text

This is <b>bold</b> and this is **strong**. This is <i>italic</i> and this is _emphasized_.
This is <sup>superscript</sup> text and this is <sub>subscript</sub> text.
This is <u>underlined</u> and this is code: `for (;;) { ... }`.
Finally, [this is a link](#).

- - - - - - -

<header markdown="1">
### Heading with a Subtitle

Lorem ipsum dolor sit amet nullam id egestas urna aliquam
</header>

Nunc lacinia ante nunc ac lobortis. Interdum adipiscing gravida odio porttitor sem non mi integer non faucibus ornare mi ut ante amet placerat aliquet. Volutpat eu sed ante lacinia sapien lorem accumsan varius montes viverra nibh in adipiscing blandit tempus accumsan.

<header markdown="1">
#### Heading with a Subtitle

Lorem ipsum dolor sit amet nullam id egestas urna aliquam
</header>

Nunc lacinia ante nunc ac lobortis. Interdum adipiscing gravida odio porttitor sem non mi integer non faucibus ornare mi ut ante amet placerat aliquet. Volutpat eu sed ante lacinia sapien lorem accumsan varius montes viverra nibh in adipiscing blandit tempus accumsan.

- - - - - - -

## Heading Level 2
### Heading Level 3
#### Heading Level 4
##### Heading Level 5
###### Heading Level 6

- - - - - - -

#### Blockquote

<blockquote>Fringilla nisl. Donec accumsan interdum nisi, quis tincidunt felis sagittis eget tempus euismod. Vestibulum ante ipsum primis in faucibus vestibulum. Blandit adipiscing eu felis iaculis volutpat ac adipiscing accumsan faucibus. Vestibulum ante ipsum primis in faucibus lorem ipsum dolor sit amet nullam adipiscing eu felis.</blockquote>

#### Preformatted

```
i = 0;

	while (!deck.isInOrder()) {
		print 'Iteration ' + i;
		deck.shuffle();
		i++;
	}

	print 'It took ' + i + ' iterations to sort the deck.';

```
</section>

<!-- Lists -->
<section markdown="1">
### Lists

<div class="row">
<div class="col-6 col-12-xsmall" markdown="1">

#### Unordered

* Dolor pulvinar etiam magna etiam.
* Sagittis adipiscing lorem eleifend.
* Felis enim feugiat dolore viverra.

#### Alternate

<ul class="alt">
	<li>Dolor pulvinar etiam magna etiam.</li>
	<li>Sagittis adipiscing lorem eleifend.</li>
	<li>Felis enim feugiat dolore viverra.</li>
	<li>Lobortis adipiscing condimentum lorem.</li>
	<li>Integer eleifend erat sed accumsan.</li>
</ul>
</div>

<div class="col-6 col-12-xsmall" markdown="1">

#### Ordered

1. Dolor pulvinar etiam magna etiam.
1. Etiam vel felis at lorem sed viverra.
1. Felis enim feugiat dolore viverra.
1. Dolor pulvinar etiam magna etiam.
1. Etiam vel felis at lorem sed viverra.
1. Felis enim feugiat dolore viverra.

#### Icons

<ul class="icons">
	<li><a href="#" class="icon fa-twitter"><span class="label">Twitter</span></a></li>
	<li><a href="#" class="icon fa-facebook"><span class="label">Facebook</span></a></li>
	<li><a href="#" class="icon fa-instagram"><span class="label">Instagram</span></a></li>
	<li><a href="#" class="icon fa-github"><span class="label">Github</span></a></li>
	<li><a href="#" class="icon fa-dribbble"><span class="label">Dribbble</span></a></li>
	<li><a href="#" class="icon fa-tumblr"><span class="label">Tumblr</span></a></li>
</ul>

<ul class="icons">
	<li><a href="#" class="icon alt fa-twitter"><span class="label">Twitter</span></a></li>
	<li><a href="#" class="icon alt fa-facebook"><span class="label">Facebook</span></a></li>
	<li><a href="#" class="icon alt fa-instagram"><span class="label">Instagram</span></a></li>
	<li><a href="#" class="icon alt fa-github"><span class="label">Github</span></a></li>
	<li><a href="#" class="icon alt fa-dribbble"><span class="label">Dribbble</span></a></li>
	<li><a href="#" class="icon alt fa-tumblr"><span class="label">Tumblr</span></a></li>
</ul>

</div>
</div>

#### Actions

<ul class="actions">
	<li><a href="#" class="button primary">Default</a></li>
	<li><a href="#" class="button">Default</a></li>
</ul>
<ul class="actions small">
	<li><a href="#" class="button primary small">Small</a></li>
	<li><a href="#" class="button small">Small</a></li>
</ul>
<div class="row">
	<div class="col-3 col-6-medium col-12-xsmall">
		<ul class="actions stacked">
			<li><a href="#" class="button primary">Default</a></li>
			<li><a href="#" class="button">Default</a></li>
		</ul>
	</div>
	<div class="col-3 col-6-medium col-12-xsmall">
		<ul class="actions stacked">
			<li><a href="#" class="button primary small">Small</a></li>
			<li><a href="#" class="button small">Small</a></li>
		</ul>
	</div>
	<div class="col-3 col-6-medium col-12-xsmall">
		<ul class="actions stacked">
			<li><a href="#" class="button primary fit">Default</a></li>
			<li><a href="#" class="button fit">Default</a></li>
		</ul>
	</div>
	<div class="col-3 col-6-medium col-12-xsmall">
		<ul class="actions stacked">
			<li><a href="#" class="button primary small fit">Small</a></li>
			<li><a href="#" class="button small fit">Small</a></li>
		</ul>
	</div>
</div>
</section>

<section markdown="1">

<!-- Table -->
### Table
<!-- damn, there's no Markdown Extra for the <tfoot> element, so good ol' HTML here for the tables -->
#### Default
<div class="table-wrapper">
	<table>
		<thead>
			<tr>
				<th>Name</th>
				<th>Description</th>
				<th>Price</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>Item 1</td>
				<td>Ante turpis integer aliquet porttitor.</td>
				<td>29.99</td>
			</tr>
			<tr>
				<td>Item 2</td>
				<td>Vis ac commodo adipiscing arcu aliquet.</td>
				<td>19.99</td>
			</tr>
			<tr>
				<td>Item 3</td>
				<td> Morbi faucibus arcu accumsan lorem.</td>
				<td>29.99</td>
			</tr>
			<tr>
				<td>Item 4</td>
				<td>Vitae integer tempus condimentum.</td>
				<td>19.99</td>
			</tr>
			<tr>
				<td>Item 5</td>
				<td>Ante turpis integer aliquet porttitor.</td>
				<td>29.99</td>
			</tr>
		</tbody>
		<tfoot>
			<tr>
				<td colspan="2"></td>
				<td>100.00</td>
			</tr>
		</tfoot>
	</table>
</div>

#### Alternate

<div class="table-wrapper">
	<table class="alt">
		<thead>
			<tr>
				<th>Name</th>
				<th>Description</th>
				<th>Price</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>Item 1</td>
				<td>Ante turpis integer aliquet porttitor.</td>
				<td>29.99</td>
			</tr>
			<tr>
				<td>Item 2</td>
				<td>Vis ac commodo adipiscing arcu aliquet.</td>
				<td>19.99</td>
			</tr>
			<tr>
				<td>Item 3</td>
				<td> Morbi faucibus arcu accumsan lorem.</td>
				<td>29.99</td>
			</tr>
			<tr>
				<td>Item 4</td>
				<td>Vitae integer tempus condimentum.</td>
				<td>19.99</td>
			</tr>
			<tr>
				<td>Item 5</td>
				<td>Ante turpis integer aliquet porttitor.</td>
				<td>29.99</td>
			</tr>
		</tbody>
		<tfoot>
			<tr>
				<td colspan="2"></td>
				<td>100.00</td>
			</tr>
		</tfoot>
	</table>
</div>
</section>

<!-- Buttons -->
<section markdown="1">

### Buttons

<ul class="actions">
	<li><a href="#" class="button primary">Primary</a></li>
	<li><a href="#" class="button">Default</a></li>
</ul>
<ul class="actions">
	<li><a href="#" class="button primary large">Large</a></li>
	<li><a href="#" class="button">Default</a></li>
	<li><a href="#" class="button small">Default</a></li>
</ul>
<div class="row">
	<div class="col-6 col-12-xsmall">
		<ul class="actions fit">
			<li><a href="#" class="button primary fit">Fit</a></li>
			<li><a href="#" class="button fit">Fit</a></li>
		</ul>
	</div>
	<div class="col-6 col-12-xsmall">
		<ul class="actions fit small">
			<li><a href="#" class="button primary fit small">Fit + Small</a></li>
			<li><a href="#" class="button fit small">Fit + Small</a></li>
		</ul>
	</div>
</div>
<ul class="actions">
	<li><a href="#" class="button primary icon fa-download">Icon</a></li>
	<li><a href="#" class="button icon fa-download">Icon</a></li>
</ul>
<ul class="actions">
	<li><span class="button primary disabled">Primary</span></li>
	<li><span class="button disabled">Default</span></li>
</ul>
</section>

<!-- Form -->
<section markdown="1">

### Form
<form method="post" action="#">
	<div class="row gtr-uniform gtr-50">
		<div class="col-6 col-12-xsmall">
			<input type="text" name="name" id="name" value="" placeholder="Name" />
		</div>
		<div class="col-6 col-12-xsmall">
			<input type="email" name="email" id="email" value="" placeholder="Email" />
		</div>
		<div class="col-12">
			<select name="category" id="category">
				<option value="">- Category -</option>
				<option value="1">Manufacturing</option>
				<option value="1">Shipping</option>
				<option value="1">Administration</option>
				<option value="1">Human Resources</option>
			</select>
		</div>
		<div class="col-4 col-12-medium">
			<input type="radio" id="priority-low" name="priority" checked>
			<label for="priority-low">Low Priority</label>
		</div>
		<div class="col-4 col-12-medium">
			<input type="radio" id="priority-normal" name="priority">
			<label for="priority-normal">Normal Priority</label>
		</div>
		<div class="col-4 col-12-medium">
			<input type="radio" id="priority-high" name="priority">
			<label for="priority-high">High Priority</label>
		</div>
		<div class="col-6 col-12-medium">
			<input type="checkbox" id="copy" name="copy">
			<label for="copy">Email me a copy of this message</label>
		</div>
		<div class="col-6 col-12-medium">
			<input type="checkbox" id="human" name="human" checked>
			<label for="human">I am a human and not a robot</label>
		</div>
		<div class="col-12">
			<textarea name="message" id="message" placeholder="Enter your message" rows="6"></textarea>
		</div>
		<div class="col-12">
			<ul class="actions">
				<li><input type="submit" value="Send Message" class="primary" /></li>
				<li><input type="reset" value="Reset" /></li>
			</ul>
		</div>
	</div>
</form>
</section>

<!-- Image -->
<section markdown="1">
### Image

#### Fit

<div class="box alt">
	<div class="row gtr-50 gtr-uniform"> <!-- NB: the images not in markdown and require Twig here because MD Extra processor inserts a para around the span, which breaks CSS -->
		<div class="col-12"><span class="image fit"><img src="{{ page.media['pic07.jpg'].url }}" alt="" /></span></div>
		<div class="col-4 col-6-xsmall"><span class="image fit"><img src="{{ page.media['pic02.jpg'].url }}" alt="" /></span></div>
		<div class="col-4 col-6-xsmall"><span class="image fit"><img src="{{ page.media['pic03.jpg'].url }}" alt="" /></span></div>
		<div class="col-4 col-6-xsmall"><span class="image fit"><img src="{{ page.media['pic04.jpg'].url }}" alt="" /></span></div>
		<div class="col-4 col-6-xsmall"><span class="image fit"><img src="{{ page.media['pic04.jpg'].url }}" alt="" /></span></div>
		<div class="col-4 col-6-xsmall"><span class="image fit"><img src="{{ page.media['pic02.jpg'].url }}" alt="" /></span></div>
		<div class="col-4 col-6-xsmall"><span class="image fit"><img src="{{ page.media['pic03.jpg'].url }}" alt="" /></span></div>
		<div class="col-4 col-6-xsmall"><span class="image fit"><img src="{{ page.media['pic03.jpg'].url }}" alt="" /></span></div>
		<div class="col-4 col-6-xsmall"><span class="image fit"><img src="{{ page.media['pic04.jpg'].url }}" alt="" /></span></div>
		<div class="col-4 col-6-xsmall"><span class="image fit"><img src="{{ page.media['pic02.jpg'].url }}" alt="" /></span></div>
		<div class="col-4 col-6-xsmall"><span class="image fit"><img src="{{ page.media['pic02.jpg'].url }}" alt="" /></span></div>
		<div class="col-4 col-6-xsmall"><span class="image fit"><img src="{{ page.media['pic03.jpg'].url }}" alt="" /></span></div>
		<div class="col-4 col-6-xsmall"><span class="image fit"><img src="{{ page.media['pic04.jpg'].url }}" alt="" /></span></div>
	</div>
</div>

#### Left &amp; Right

<span class="image left">![](pic08.jpg)</span>Fringilla nisl. Donec accumsan interdum nisi, quis tincidunt felis sagittis eget. tempus euismod. Vestibulum ante ipsum primis in faucibus vestibulum. Blandit adipiscing eu felis iaculis volutpat ac adipiscing accumsan eu faucibus. Integer ac pellentesque praesent tincidunt felis sagittis eget. tempus euismod. Vestibulum ante ipsum primis in faucibus vestibulum. Blandit adipiscing eu felis iaculis volutpat ac adipiscing accumsan eu faucibus. Integer ac pellentesque praesent. Donec accumsan interdum nisi, quis tincidunt felis sagittis eget. tempus euismod. Vestibulum ante ipsum primis in faucibus vestibulum. Blandit adipiscing eu felis iaculis volutpat ac adipiscing accumsan eu faucibus. Integer ac pellentesque praesent tincidunt felis sagittis eget. tempus euismod. Vestibulum ante ipsum primis in faucibus vestibulum. Blandit adipiscing eu felis iaculis volutpat ac adipiscing accumsan eu faucibus. Integer ac pellentesque praesent. Cras aliquet accumsan curae accumsan arcu amet egestas placerat odio morbi mi adipiscing col morbi felis faucibus in gravida sollicitudin interdum commodo. Ante aliquam vis iaculis accumsan lorem ipsum dolor sit amet nullam. Cras aliquet accumsan curae accumsan arcu amet egestas placerat odio morbi mi adipiscing col morbi felis faucibus in gravida sollicitudin interdum commodo. Ante aliquam vis iaculis accumsan lorem ipsum dolor sit amet nullam.

<span class="image right">![](pic08.jpg)</span>Fringilla nisl. Donec accumsan interdum nisi, quis tincidunt felis sagittis eget. tempus euismod. Vestibulum ante ipsum primis in faucibus vestibulum. Blandit adipiscing eu felis iaculis volutpat ac adipiscing accumsan eu faucibus. Integer ac pellentesque praesent tincidunt felis sagittis eget. tempus euismod. Vestibulum ante ipsum primis in faucibus vestibulum. Blandit adipiscing eu felis iaculis volutpat ac adipiscing accumsan eu faucibus. Integer ac pellentesque praesent. Donec accumsan interdum nisi, quis tincidunt felis sagittis eget. tempus euismod. Vestibulum ante ipsum primis in faucibus vestibulum. Blandit adipiscing eu felis iaculis volutpat ac adipiscing accumsan eu faucibus. Integer ac pellentesque praesent tincidunt felis sagittis eget. tempus euismod. Vestibulum ante ipsum primis in faucibus vestibulum. Blandit adipiscing eu felis iaculis volutpat ac adipiscing accumsan eu faucibus. Integer ac pellentesque praesent. Cras aliquet accumsan curae accumsan arcu amet egestas placerat odio morbi mi adipiscing col morbi felis faucibus in gravida sollicitudin interdum commodo. Ante aliquam vis iaculis accumsan lorem ipsum dolor sit amet nullam. Cras aliquet accumsan curae accumsan arcu amet egestas placerat odio morbi mi adipiscing col morbi felis faucibus in gravida sollicitudin interdum commodo. Ante aliquam vis iaculis accumsan lorem ipsum dolor sit amet nullam.

</section>
