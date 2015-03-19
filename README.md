# The-Republic-of-Music
Javascript/jQuery for landing page
$(document).on('ready', function() {
	$ ('li').on('click', function()	{
		$(this).animate({
			opacity:	0.0,
			paddingLeft:	'+=80'
		}, 500, function()	{
			$ (this).remove();
		});
	});
});
