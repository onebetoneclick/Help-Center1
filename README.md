<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Support Button Link</title>
    <style>
        /* BUTTON HOUSING POSITIONING */
        .support-btn-container {
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }

        /* PREMIUM BLUE & WHITE FLOATING CHAT BUTTON */
        .live-chat-link-btn {
            display: inline-flex;
            align-items: center;
            gap: 12px;
            padding: 14px 28px;
            background: linear-gradient(135deg, #2563eb, #1d4ed8);
            color: #ffffff;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            font-size: 15px;
            font-weight: 700;
            text-decoration: none;
            border-radius: 50px;
            box-shadow: 0 4px 15px rgba(29, 78, 216, 0.35);
            border: 1px solid rgba(255, 255, 255, 0.1);
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
            cursor: pointer;
        }

        /* HARDWARE-ACCELERATED HOVER INTERACTIONS */
        .live-chat-link-btn:hover {
            transform: translateY(-3px);
            background: linear-gradient(135deg, #3b82f6, #2563eb);
            box-shadow: 0 8px 25px rgba(59, 130, 246, 0.5);
            border-color: rgba(255, 255, 255, 0.2);
        }

        .live-chat-link-btn:active {
            transform: translateY(-1px);
            box-shadow: 0 4px 10px rgba(29, 78, 216, 0.3);
        }

        /* ANIMATED TALK BUBBLE SVG ICON */
        .live-chat-link-btn svg {
            transition: transform 0.3s ease;
        }

        .live-chat-link-btn:hover svg {
            transform: rotate(-8deg) scale(1.1);
        }
    </style>
</head>
<body>

    <!-- RENDER WRAPPER FOR STORE INTEGRATION -->
    <div class="support-btn-container">
        
        <!-- TARGETED FLOATING LINK COMPONENT pointing straight to your CodePen live view -->
        <a href="[https://codepen.io](https://codepen.io/Yusuf-Rokib/full/LExWzKO)" target="_blank" class="live-chat-link-btn">
            <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round">
                <path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"></path>
            </svg>
            <span>Open WhatsApp Live Support</span>
        </a>

    </div>

</body>
</html>


