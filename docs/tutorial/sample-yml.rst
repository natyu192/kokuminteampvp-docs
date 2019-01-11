config.yml のサンプル
=======================

::

	name: 'Kokumin Wars'
	gametype: CTW
	allow-build: true
	fall-damage: true
	teams:
	  red:
	    name: 'Red Team'
	    color: red
	    max: 16
	  blue:
	    name: 'Blue Team'
	    color: blue
	    max: 16
	wools:
	  lightblue:
	    team: blue
	    color: light_blue
	    x: 1
	    y: 15
	    z: -133
	  cyan:
	    team: blue
	    color: cyan
	    x: -2
	    y: 15
	    z: -133
	  purple:
	    team: red
	    color: purple
	    x: -2
	    y: 15
	    z: 133
	  pink:
	    team: red
	    color: pink
	    x: 1
	    y: 15
	    z: 133
	regions:
	  bluebase:
	    team: blue
	    name: 'Blue Base'
	    enter: false
	    pos1:
	      x: -15.5
	      y: 0
	      z: -135
	    pos2:
	      x: 15.5
	      y: 255
	      z: -118.5
	    deny-message: '敵のチームの拠点に入ることはできません'
	  redbase:
	    team: red
	    name: 'Red Base'
	    enter: false
	    pos1:
	      x: 15.5
	      y: 0
	      z: 135.5
	    pos2:
	      x: -15.5
	      y: 255
	      z: 118.5
	    deny-message: '敵のチームの拠点に入ることはできません'
	  purplewool:
	    team: red
	    name: 'Purple Wool Room'
	    enter: false
	    pos1:
	      x: -41.5
	      y: 0.0
	      z: -105.5
	    pos2:
	      x: -57.5
	      y: 255.0
	      z: -116.5
	  pinkwool:
	    team: red
	    name: 'Pink Wool Room'
	    enter: false
	    pos1:
	      x: 57.5
	      y: 0.0
	      z: -105.5
	    pos2:
	      x: 41.5
	      y: 255
	      z: -116.5
	  lightbluewool:
	    team: blue
	    name: 'Light Blue Wool Room'
	    enter: false
	    pos1:
	      x: -41.5
	      y: 0.0
	      z: 116.5
	    pos2:
	      x: -57.5
	      y: 255.0
	      z: 105.5
	  cyanwool:
	    team: blue
	    name: 'Cyan Wool Room'
	    enter: false
	    pos1:
	      x: 41.5
	      y: 0.0
	      z: 105.5
	    pos2:
	      x: 57.5
	      y: 255.0
	      z: 116.5
	location:
	  red:
	    x: 0.0
	    y: 14.5
	    z: 128.0
	    yaw: -180
	    pitch: 0
	  blue:
	    x: 0.0
	    y: 14.5
	    z: -127.0
	    yaw: 0
	    pitch: 0
	  spectator:
	    x: -51.5
	    y: 46
	    z: 0.5
	    yaw: -90
	    pitch: 0
	kits:
	  red:
	    armor:
	      helmet:
	        material: LEATHER_HELMET
	        slot: 40
	        leather_color: RED
	        soulbound: true
	      chestplate:
	        material: LEATHER_CHESTPLATE
	        slot: 41
	        leather_color: RED
	        soulbound: true
	      leggings:
	        material: LEATHER_LEGGINGS
	        slot: 42
	        leather_color: RED
	        soulbound: true
	      boots:
	        material: LEATHER_BOOTS
	        slot: 43
	        leather_color: RED
	        soulbound: true
	  blue:
	    armor:
	      helmet:
	        material: LEATHER_HELMET
	        slot: 40
	        leather_color: BLUE
	        soulbound: true
	      chestplate:
	        material: LEATHER_CHESTPLATE
	        slot: 41
	        leather_color: BLUE
	        soulbound: true
	      leggings:
	        material: LEATHER_LEGGINGS
	        slot: 42
	        leather_color: BLUE
	        soulbound: true
	      boots:
	        material: LEATHER_BOOTS
	        slot: 43
	        leather_color: BLUE
	        soulbound: true
	  parent:
	    inventory:
	      sword:
	        material: IRON_SWORD
	        slot: 0
	        soulbound: true
	      bow:
	        material: BOW
	        slot: 1
	        soulbound: true
	      food:
	        material: BAKED_POTATO
	        slot: 2
	        amount: 16
	        soulbound: true
	      pickaxe:
	        material: DIAMOND_PICKAXE
	        slot: 3
	        soulbound: true
	      axe:
	        material: DIAMOND_AXE
	        slot: 4
	        soulbound: true
	      log:
	        material: LOG
	        slot: 5
	        amount: 32
	        soulbound: true
	      arrow:
	        material: ARROW
	        slot: 9
	        amount: 64
	        soulbound: true
	  kill-rewards:
	    gapple:
	      material: GOLDEN_APPLE
	      amount: 1
	      soulbound: false