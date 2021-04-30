const Discord = require('discord.js');
const client = new Discord.Client();

client.on('message', async message => {

//Ping Pong
if(message.content === 'ping') {
message.channel.send('PONG!')
}

//Embed
if(message.content === 'embed') {
const embed = new Discord.MessageEmbed()
.setTitle('This Is The Title')
.setDescription('This Is The Description')
.setFooter('This Is The Footer')
.setColor('RANDOM')
message.channel.send(embed)
}

//Bot Token
client.login('YOUR-TOKEN-HERE);
