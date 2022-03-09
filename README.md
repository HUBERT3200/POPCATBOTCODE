# POPCATBOTCODE

Link do instrukcji: https://youtu.be/bhCKnudm69k

KOD:
var event = new KeyboardEvent('keydown', {
	key: 'g',
	ctrlKey: true
});

setInterval(function(){
	for (i = 0; i < 100; i++) {
		document.dispatchEvent(event);
	}
}, 0);
