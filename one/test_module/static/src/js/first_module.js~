// static/src/js/first_module.js
openerp.test_module = function (instance) {
	instance.web.client_actions.add('example.action', 'instance.test_module.Action');
	instance.test_module.Action = instance.web.Widget.extend({
	        className: 'oe_web_example',
	        start: function () {
	        	this.$el.text("Hello, world!");
            		return this._super();
        	}
    	});
 };
