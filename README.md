# 1kp-2019
1000 Pitches Website

TO-DO
1. links for all buttons + Visit us on FB
2. Bug: when u switch to dark mode, a small opacity: 1 (i think) blue spot appears on the canvas before u start drawing.
This did not solve it:
setTimeout(function() {
    	window.canvas.setHeight(window.innerHeight - 1); // get rid of old canvas
    	window.canvas.setHeight(window.innerHeight); // get rid of old canvas
    	}, 800);