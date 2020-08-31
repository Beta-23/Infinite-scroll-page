```JavaScript 
// Event Listener Checks to see if scrolling near bottom of page, Load More Photos
window.addEventListener('scroll', () => {
	if (window.innerHeight + window.scrollY >= document.body.offsetHeight - 1000) {
		console.log('window.innerHeight', window.innerHeight);
		console.log('window.scrollY', window.scrollY);
		console.log('window.innerHeight + scrollY:', window.scrollY + window.innerHeight);
		console.log('document.body.offsetHeight - 1000:', document.body.offsetHeight - 1000);
		console.log('load more...');
	}
});
```