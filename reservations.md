---
layout: aboutus
title: Coyote Flaco Reservation
permalink: reservations.html
---



<div id="tm-header-a" class="tm-block-header-a uk-block uk-block-default tm-block-fullwidth tm-grid-collapse uk-margin-large-bottom">
	<div class="uk-container uk-container-center">
		<section class="tm-header-a uk-grid" data-uk-grid-match="{target:'> div > .uk-panel'}">
			<div class="uk-width-1-1">
				<div class="uk-panel uk-text-center uk-contrast tm-overlay-secondary tm-header-height">
					<div class="tm-background-cover uk-cover-background uk-flex uk-flex-center uk-flex-middle" style="background-position: 50% 0px; background-image: url('images/generic-patio.jpg'); background-size: auto; background-repeat: no-repeat;" data-uk-parallax="{bg: '-200'}">
						<div class="uk-position-relative uk-container" style="width: 100%;">
							<div data-uk-parallax="{opacity: '1,0', y: '-50'}" style="transform: translate3d(0px, 0px, 0px); opacity: 1;">
								<div class="uk-scrollspy-init-inview uk-scrollspy-inview uk-animation-slide-top">
									<h1 class="uk-margin-top uk-text-center cf-heading">
                      {% include left-arrows.html %}
                      Reservations
                      {% include right-arrows.html %}</h1>
								</div>
								<div class="uk-scrollspy-init-inview uk-scrollspy-inview uk-animation-slide-top">
									<h5 class="uk-sub-title-small">If you can dream it, you can do it</h5>
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
		</section>
	</div>
</div>
<!-- Conditional Section -->
<div class="uk-container uk-container-center">
  <ul id="profileTabs" class="nav nav-tabs uk-tab uk-tab-grid uk-tab-top uk-text-center" style="margin-left: 5em !important;">
      <li class="active">
        <a class="noCrossRef" href="#profile" data-toggle="tab" aria-expanded="true" style="font-size:1.25em;">
          Hartford Reservation
        </a>
      </li>
      <li class="">
        <a class="noCrossRef" href="#about" data-toggle="tab" aria-expanded="false" style="font-size:1.25em;">
          Mansfield Reservation
        </a>
      </li> 
  </ul>
  <div class="tab-content uk-margin" style="margin-top: 0px !important;">
      <div role="tabpanel" class="tab-pane active" id="profile">
          {%include cf-reservations.html %}
      </div>
      <div role="tabpanel" class="tab-pane" id="about">
          {%include cfm-reservations.html %}
      </div>
  </div>
</div>
{% include cfh-footer.html %}










<!-- Latest compiled and minified CSS -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">

<!-- Latest compiled and minified JavaScript -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>

<style>
.uk-margin-small-top {
    margin-top: 15px !important;
    margin-bottom: 15px !important;
}
  </style>