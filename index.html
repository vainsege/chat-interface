<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ChatGPT Interface</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }
    
    body {
      background-color: #f7f7f8;
      display: flex;
      height: 100vh;
    }
    
    .sidebar {
      width: 260px;
      background-color: #202123;
      color: white;
      padding: 10px;
      display: flex;
      flex-direction: column;
    }
    
    .new-chat {
      border: 1px solid rgba(255, 255, 255, 0.2);
      border-radius: 6px;
      padding: 12px;
      margin-bottom: 20px;
      cursor: pointer;
      display: flex;
      align-items: center;
      gap: 12px;
      transition: background-color 0.2s;
    }
    
    .new-chat:hover {
      background-color: #2d2d30;
    }
    
    .chat-history {
      flex-grow: 1;
      overflow-y: auto;
    }
    
    .history-item {
      padding: 10px;
      margin-bottom: 5px;
      border-radius: 6px;
      cursor: pointer;
      display: flex;
      align-items: center;
      gap: 12px;
      color: rgba(255, 255, 255, 0.8);
    }
    
    .history-item:hover {
      background-color: #2d2d30;
    }
    
    .user-info {
      padding: 12px;
      display: flex;
      align-items: center;
      gap: 10px;
      border-top: 1px solid rgba(255, 255, 255, 0.1);
      margin-top: auto;
    }
    
    .avatar {
      width: 36px;
      height: 36px;
      background-color: #5a5a5a;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      font-weight: bold;
    }
    
    .main-content {
      flex-grow: 1;
      display: flex;
      flex-direction: column;
      height: 100%;
    }
    
    .chat-container {
      flex-grow: 1;
      padding: 20px;
      overflow-y: auto;
      display: flex;
      flex-direction: column;
      gap: 24px;
    }
    
    .message {
      display: flex;
      gap: 20px;
      padding: 20px;
      max-width: 800px;
      margin: 0 auto;
      width: 100%;
    }
    
    .user-message {
      background-color: #ffffff;
    }
    
    .ai-message {
      background-color: #f7f7f8;
    }
    
    .message-avatar {
      width: 36px;
      height: 36px;
      border-radius: 4px;
      display: flex;
      align-items: center;
      justify-content: center;
      flex-shrink: 0;
    }
    
    .user-avatar {
      background-color: #5436da;
      color: white;
    }
    
    .ai-avatar {
      background-color: #10a37f;
      color: white;
    }
    
    .message-content {
      flex-grow: 1;
      line-height: 1.6;
    }
    
    .input-container {
      padding: 20px;
      display: flex;
      justify-content: center;
      background-color: #f7f7f8;
      border-top: 1px solid #e5e5e6;
      position: relative;
    }
    
    .input-box {
      display: flex;
      align-items: center;
      width: 100%;
      max-width: 800px;
      position: relative;
    }
    
    .input-field {
      width: 100%;
      padding: 14px 50px 14px 14px;
      border: 1px solid #e5e5e6;
      border-radius: 6px;
      font-size: 16px;
      line-height: 1.5;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.05);
      resize: none;
      max-height: 200px;
      min-height: 52px;
      overflow-y: auto;
    }
    
    .input-field:focus {
      outline: none;
      border-color: #10a37f;
    }
    
    .send-button {
      position: absolute;
      right: 10px;
      top: 50%;
      transform: translateY(-50%);
      background-color: transparent;
      border: none;
      cursor: pointer;
      color: #10a37f;
      display: flex;
      align-items: center;
      justify-content: center;
      width: 32px;
      height: 32px;
      border-radius: 4px;
    }
    
    .send-button:hover {
      background-color: rgba(16, 163, 127, 0.1);
    }
    
    .model-info {
      font-size: 12px;
      color: #6e6e80;
      text-align: center;
      margin-bottom: 10px;
    }
    
    @media (max-width: 768px) {
      .sidebar {
        display: none;
      }
      
      .message {
        padding: 15px;
      }
    }
  </style>
</head>
<body>
  <!-- Sidebar -->
  <div class="sidebar">
    <div class="new-chat">
      <svg stroke="currentColor" fill="none" stroke-width="2" viewBox="0 0 24 24" height="16" width="16" xmlns="http://www.w3.org/2000/svg"><line x1="12" y1="5" x2="12" y2="19"></line><line x1="5" y1="12" x2="19" y2="12"></line></svg>
      New chat
    </div>
    
    <div class="chat-history">
      <div class="history-item">
        <svg stroke="currentColor" fill="none" stroke-width="2" viewBox="0 0 24 24" height="16" width="16" xmlns="http://www.w3.org/2000/svg"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"></path></svg>
        Introduction to Machine Learning
      </div>
      <div class="history-item">
        <svg stroke="currentColor" fill="none" stroke-width="2" viewBox="0 0 24 24" height="16" width="16" xmlns="http://www.w3.org/2000/svg"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"></path></svg>
        JavaScript Project Help
      </div>
      <div class="history-item">
        <svg stroke="currentColor" fill="none" stroke-width="2" viewBox="0 0 24 24" height="16" width="16" xmlns="http://www.w3.org/2000/svg"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"></path></svg>
        Book Recommendations
      </div>
    </div>
    
    <div class="user-info">
      <div class="avatar">U</div>
      <div>User Account</div>
    </div>
  </div>
  
  <!-- Main Content -->
  <div class="main-content">
    <div class="chat-container">
      <!-- AI Message -->
      <div class="message ai-message">
        <div class="message-avatar ai-avatar">AI</div>
        <div class="message-content">
          Hello! I'm an AI assistant. How can I help you today?
        </div>
      </div>
      
      <!-- User Message -->
      <div class="message user-message">
        <div class="message-avatar user-avatar">U</div>
        <div class="message-content">
          Can you help me understand how to create a responsive web design?
        </div>
      </div>
      
      <!-- AI Message -->
      <div class="message ai-message">
        <div class="message-avatar ai-avatar">AI</div>
        <div class="message-content">
          Absolutely! Responsive web design is an approach to web design that makes web pages render well on a variety of devices and window or screen sizes.<br><br>
          
          Here are the key principles of responsive design:<br><br>
          
          1. Fluid grids - Using relative units like percentages instead of fixed units like pixels<br>
          2. Flexible images - Images that can scale up and down<br>
          3. Media queries - CSS techniques that apply different styles for different screen sizes<br><br>
          
          Would you like me to explain any of these principles in more detail?
        </div>
      </div>
    </div>
    
    <div class="model-info">
      Model: ChatGPT-4
    </div>
    
    <div class="input-container">
      <div class="input-box">
        <textarea class="input-field" placeholder="Send a message..." rows="1"></textarea>
        <button class="send-button">
          <svg stroke="currentColor" fill="none" stroke-width="2" viewBox="0 0 24 24" height="16" width="16" xmlns="http://www.w3.org/2000/svg"><line x1="22" y1="2" x2="11" y2="13"></line><polygon points="22 2 15 22 11 13 2 9 22 2"></polygon></svg>
        </button>
      </div>
    </div>
  </div>
</body>
</html>
