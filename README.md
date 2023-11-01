# NaanMudhalavan-IBM-Chatbot

*1.Installation*

Clone the repository to your local machine:

git clone https://github.com/YathindrapravananTV/Naan-mudhalvan-IBM-Chatbot/

*2.API Keys*

Use the following API Key
RM4FQD8VcJvbwzjw6OpsS2Ul3WBJzVrtnc5OeBqQ8-hl

*3.Deploy the Chatbot*
Go to the Publish tag and update the changes

Use the following JavaScript code snippet to integrate Sherlock Chatbot into your website. 

`<script>
  window.watsonAssistantChatOptions = {
    integrationID: "629089c7-a786-4083-bed9-1caf27e6f83e", // The ID of this integration.
    region: "eu-gb", // The region your integration is hosted in.
    serviceInstanceID: "1322a9ba-af9a-4edf-abfc-f0bd534f3cb7", // The ID of your service instance.
    onLoad: async (instance) => { await instance.render(); }
  };
  setTimeout(function(){
    const t=document.createElement('script');
    t.src="https://web-chat.global.assistant.watson.appdomain.cloud/versions/" + (window.watsonAssistantChatOptions.clientVersion || 'latest') + "/WatsonAssistantChatEntry.js";
    document.head.appendChild(t);
  });
</script>`
