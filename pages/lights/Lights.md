---
title: Lighting Home Page
layout: page
comments: true
sidebar: main_sidebar
topnav: topnav
image_folder: images
document_folder: documents
keywords: lights
summary: null
permalink: lights.html
folder: lights
toc: false
---

<div class="row">
	<div class="col-lg-12">
		<!--<h2 class="page-header">Service List</h2>-->
	</div>
	<div class="col-md-4">
		<div class="media">
      <div class="pull-left">
        <span class="fa-stack fa-2x"><i class="fa fa-circle fa-stack-2x text-primary"></i> <i class="fa fa-check fa-stack-1x fa-inverse"></i></span>
      </div>
			<div class="media-body">
				<h3 class="media-heading" markdown="1">[Pre-Service Checklist](/pre_service_checklist.html)</h3>
				<p>Guide to starting up a service.</p>
			</div>
		</div>
		<div class="media">
      <div class="pull-left">
        <span class="fa-stack fa-2x"><i class="fa fa-circle fa-stack-2x text-primary"></i> <i class="fa fa-music fa-stack-1x fa-inverse"></i></span>
      </div>
			<div class="media-body">
				<h3 class="media-heading">DMXIS and Touch OSC</h3>
				<p markdown="1">[Overview](/osc-reference-for-dmxis.html)</p>
			</div>
		</div>
		<!--<div class="media">
			<div class="pull-left">
				<span class="fa-stack fa-2x"><i class="fa fa-circle fa-stack-2x text-primary"></i> <i class="fa fa-support fa-stack-1x fa-inverse"></i></span>
			</div>
			<div class="media-body">
				<h4 class="media-heading">Service Three</h4>
				<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illo itaque ipsum sit harum.</p>
			</div>
		</div>--->
	</div>
	<div class="col-md-4">
		<div class="media">
			<div class="pull-left">
        <span class="fa-stack fa-2x"><i class="fa fa-circle fa-stack-2x text-primary"></i> <i class="fa fa-tv fa-stack-1x fa-inverse"></i></span>
      </div>
			<div class="media-body">
				<h3 class="media-heading" markdown="1">[Equipment List](/equipment_list_lights.html)</h3>
				<p>A list of the audio gear in use.</p>
			</div>
		</div>
		<div class="media">
			<!--<div class="pull-left">
				<span class="fa-stack fa-2x"><i class="fa fa-circle fa-stack-2x text-primary"></i> <i class="fa fa-bomb fa-stack-1x fa-inverse"></i></span>
			</div>
			<div class="media-body">
				<h4 class="media-heading">Service Five</h4>
				<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illo itaque ipsum sit harum.</p>
			</div>-->
		</div>
		<div class="media">
			<!--<div class="pull-left">
				<span class="fa-stack fa-2x"><i class="fa fa-circle fa-stack-2x text-primary"></i> <i class="fa fa-bank fa-stack-1x fa-inverse"></i></span>
			</div>
			<div class="media-body">
				<h4 class="media-heading">Service Six</h4>
				<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illo itaque ipsum sit harum.</p>
			</div>-->
		</div>
	</div>
	<div class="col-md-4">
		<div class="media">
			<div class="pull-left">
        <span class="fa-stack fa-2x"><i class="fa fa-circle fa-stack-2x text-primary"></i> <i class="fa fa-ticket fa-stack-1x fa-inverse"></i></span>
      </div>
			<div class="media-body">
				<h3 class="media-heading" markdown="1">[Troubleshooting / FAQ](/faq_lights.html)</h3>
				<p markdown="1">Questions and answers to your most common sound problems.</p>
			</div>
		</div>
		<div class="media">
			<!--<div class="pull-left">
				<span class="fa-stack fa-2x"><i class="fa fa-circle fa-stack-2x text-primary"></i> <i class="fa fa-space-shuttle fa-stack-1x fa-inverse"></i></span>
			</div>
			<div class="media-body">
				<h4 class="media-heading">Service Eight</h4>
				<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illo itaque ipsum sit harum.</p>
			</div>-->
		</div>
		<div class="media">
			<!--<div class="pull-left">
				<span class="fa-stack fa-2x"><i class="fa fa-circle fa-stack-2x text-primary"></i> <i class="fa fa-recycle fa-stack-1x fa-inverse"></i></span>
			</div>
			<div class="media-body">
				<h4 class="media-heading">Service Nine</h4>
				<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illo itaque ipsum sit harum.</p>
			</div>-->
		</div>
	</div>
</div>

## About The Lights

New Valley's sanctuary lighting system consists of a single DMX Universe controlled by a single DMX 512 Channel USB Hardware controller connected to the FOH media computer.

The single Universe is split by the D-Split device attached to the DMXIS controller into two desintations.

The first line feeds all 9 stage lights in series without a terminator.  Terminators are usually needed on long cable runs.  Our cable run is relatively short so it's not yet an issue.

The 2nd feed terminates in the office behind the FOH control booth at a Leviton DS8 Dimmer pack.  The dimmer pack is considered a single light with 8 channels.

Each light occupies a certain number of channels depending upon the number of functions it supports.  Each channel of each light uses one of the 512 available channels in the universe.

### Stage and FOH

There are 7 FOH lights including 5 RBGA LED lamps and 2 Unicolor white/strobes.
There are 2 additional "electrics" which are also unicolor white/strobes hanging directly over the stage.

(Stage lighting hanging in front of the stage apron is considered "Front of House."  Lighting that is over the stage are referred to as "electrics.")

### House Lights

House lights are controlled by a Leviton 8-Channel DMX Dimmer Pack which is connected to the DMX lighting system.  Signals reach the dimmer pack through the Ethernet to DMX converter (Enttec ODE Mk2).  Channel 8 on the dimmer pack is unused.

Signals to control the lights originate from any compatible device attached to the network.  This could be a computer workstation, a mobile device, a Raspberry Pi3, etc.  



{% include links.html %}
