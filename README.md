# hello-world
const Discord = require('discord.js');
const client = new Discord.Client();

client.on('ready', () => {
  console.log(`Logged in as ${client.user.tag}!`);
});

client.on('message', msg => {
  if (msg.content === 'ping') {
    msg.reply('Pong!');
  }
});

client.login('NzU3OTg4MzU0OTc2NTE0MDY4.X2oZqg.C11KJipAeQ185ERWMDMJa12TuT4');
