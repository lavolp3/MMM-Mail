# Module: MMM-Mail

The lightwight E-Mail Scanner for your mirror with integrated "NEW-Mail" Alert

## Install

To install the module, just clone this repository to your __modules__ folder: `git clone https://github.com/ronny3050/email-mirror.git email`. 
Then run `cd email` and `npm install` which will install the dependencies.

## Using

To use this module, add it to the modules array in the `config/config.js` file:

````javascript
modules: [
	{
		module: 'MMM-Mail',
            position: 'bottom_left',
            header: 'Email',
            config:{
                user: 'johndoe@gmail.com',
                password: 'xxx',
                host: 'imap.gmail.com',
                port: 993,
                numberOfEmails: 5,
                fade: true
        },
	}
]
````

## Configuration options

The following properties can be configured:


<table width="100%">
	<!-- why, markdown... -->
	<thead>
		<tr>
			<th>Option</th>
			<th width="100%">Description</th>
		</tr>
	<thead>
	<tbody>
		<tr>
			<td><code>user</code></td>
			<td>Full email address of the user<br>
			</td>
		</tr>
		<tr>
			<td><code>pass</code></td>
			<td>Email password<br>
			</td>
		</tr>
		<tr>
			<td><code>host</code></td>
			<td>IMAP hostname<br>
			</td>
		</tr>
		<tr>
			<td><code>port</code></td>
			<td>Port that imap uses
				<br><b>Default value:</b> <code>993</code>
			</td>
		</tr>
		<tr>
			<td><code>numberOfEmails</code></td>
			<td>Number of emails to display at a time<br>
				<br><b>Default value:</b> <code>5</code>
			</td>
		</tr>
		<tr>
			<td><code>fade</code></td>
			<td>Fade older emails to black. (Gradient)<br>
				<br><b>Possible values:</b> <code>true</code> or <code>false</code>
				<br><b>Default value:</b> <code>true</code>
			</td>
		</tr>
	</tbody>
</table>

# Special Thanks to Ronny 
(I used his Frontend and some Backend inspiration)
you can find his module on <href> https://github.com/ronny3050/email-mirror </>

