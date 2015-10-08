## Getting Started
This plugin requires [Grunt](http://gruntjs.com/) `~0.4.1`

	npm install grunt-tsfmt --save-dev

Once the plugin has been installed, it may be enabled inside your Gruntfile with this line of JavaScript:

	grunt.loadNpmTasks('grunt-tsfmt');

## The "tsfmt" task

### Overview
In your project's Gruntfile, add a section named `tsfmt` to the data object passed into `grunt.initConfig()`.

	grunt.initConfig({
	  tsfmt: {
	    options: {
    	  // Task-specific options go here.
	    },
	    files: {
    	  // Files to format go here
	    },
	  },
	})

### Options

#### options.configuration
Type: `Object`

A JSON configuration object passed into tsfmt.

### Usage Example

	grunt.initConfig({
	  tsfmt: {
	    files: {
	      src: ['src/file1.ts', 'src/file2.ts']
	    }
	  }
	})
