# O-Card [![Build Status](https://travis-ci.org/Pearson-Higher-Ed/o-card.svg)](https://travis-ci.org/Pearson-Higher-Ed/o-card)

A set of classes to define sizing for all the cards and their respective sizes within an application.

The class definition only sets the height of the card and are all variabled.  The width is not set because the layouts will control widths.  This is needed because the layouts are what decide how the card will be moved expanded and contracted through responsive designs.

## Use

### Example HTML
	<div class="container-small">
		<div class="o-card o-card--small">
			I am a small
		</div>
	</div>
	<div class="container-medium">
		<div class="o-card o-card--medium">
			i am a medium
		</div>
	</div>
	<div class="container-medium-wide">
		<div class="o-card o-card--medium">
			i am a medium wide
		</div>
	</div>
	<div class="container-large">
		<div class="o-card o-card--large">
			i am a large
		</div>
	</div>
