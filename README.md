# grunt-repeat
repeat a task several times

## Installation
`npm install git://github.com/Malkiz/grunt-repeat --save-dev`

`grunt.loadNpmTasks('grunt-repeat');`

## Config
```javascript
repeat: {
	test: {
		options: {
			times: 5,
			task: 'some-task:bla'
		}
	}
}
```
