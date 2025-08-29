<div class="container">
        <header>
            <h1>Xzor</h1>
            <p class="subtitle">Gaming Enthusiast & Digital Warrior</p>
        </header>
        <div class="profile-section">
            <h2 class="section-title">Connect With Me</h2>
            <div class="social-links">
                <a href="https://discordapp.com/users/xzor_" class="social-link" target="_blank">
                    <svg class="discord-icon" viewBox="0 0 24 24">
                        <path d="M20.317 4.37a19.791 19.791 0 0 0-4.885-1.515.074.074 0 0 0-.079.037c-.21.375-.444.864-.608 1.25a18.27 18.27 0 0 0-5.487 0 12.64 12.64 0 0 0-.617-1.25.077.077 0 0 0-.079-.037A19.736 19.736 0 0 0 3.677 4.37a.07.07 0 0 0-.032.027C.533 9.046-.32 13.58.099 18.057a.082.082 0 0 0 .031.057 19.9 19.9 0 0 0 5.993 3.03.078.078 0 0 0 .084-.028c.462-.63.874-1.295 1.226-1.994a.076.076 0 0 0-.041-.106 13.107 13.107 0 0 1-1.872-.892.077.077 0 0 1-.008-.128 10.2 10.2 0 0 0 .372-.292.074.074 0 0 1 .077-.010c3.928 1.793 8.18 1.793 12.062 0a.074.074 0 0 1 .078.01c.120.098.246.196.373.292a.077.077 0 0 1-.006.127 12.299 12.299 0 0 1-1.873.892.077.077 0 0 0-.041.107c.36.698.772 1.362 1.225 1.993a.076.076 0 0 0 .084.028 19.839 19.839 0 0 0 6.002-3.03.077.077 0 0 0 .032-.054c.5-5.177-.838-9.674-3.549-13.66a.061.061 0 0 0-.031-.03zM8.02 15.33c-1.183 0-2.157-1.085-2.157-2.419 0-1.333.956-2.419 2.157-2.419 1.21 0 2.176 1.096 2.157 2.42 0 1.333-.956 2.418-2.157 2.418zm7.975 0c-1.183 0-2.157-1.085-2.157-2.419 0-1.333.955-2.419 2.157-2.419 1.21 0 2.176 1.096 2.157 2.42 0 1.333-.946 2.418-2.157 2.418z"/>
                    </svg>
                    Discord Profile
                </a>
            </div>
        </div>
        <div class="profile-section">
            <h2 class="section-title">Gaming Stats</h2>
            <div class="stats-grid">
                <div class="stat-card">
                    <div class="stat-number">∞</div>
                    <div class="stat-label">Hours Played</div>
                </div>
                <div class="stat-card">
                    <div class="stat-number">∞</div>
                    <div class="stat-label">Games Owned</div>
                </div>
                <div class="stat-card">
                    <div class="stat-number">∞</div>
                    <div class="stat-label">Achievements</div>
                </div>
                <div class="stat-card">
                    <div class="stat-number">∞</div>
                    <div class="stat-label">Friends Online</div>
                </div>
            </div>
        </div>
        <div class="profile-section">
            <h2 class="section-title">Currently Playing</h2>
            <div class="games-list">
                <div class="game-item">
                    <div class="game-title">Your Favorite Game</div>
                    <div class="game-status">Level ∞ • Online</div>
                </div>
                <div class="game-item">
                    <div class="game-title">Another Game</div>
                    <div class="game-status">Mastery Unlocked</div>
                </div>
                <div class="game-item">
                    <div class="game-title">Epic Adventure</div>
                    <div class="game-status">Quest Complete</div>
                </div>
            </div>
        </div>
        <div class="profile-section">
            <h2 class="section-title">About Me</h2>
            <p style="color: #8b949e; font-size: 1.1rem; line-height: 1.8;">
                Welcome to my gaming profile! I'm Xzor, a passionate gamer who loves exploring virtual worlds,
                competing in challenging matches, and connecting with fellow gamers. Whether it's strategy games,
                FPS, RPGs, or indie gems, I'm always ready for the next adventure.
            </p>
        </div>
        <footer>
            <p>&copy; 2024 Xzor Gaming Profile. Game on!</p>
        </footer>
    </div>

<style>
body {
    margin: 0;
    padding: 0;
    background-color: #0e1117;
    color: #fff;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    overflow: hidden;
}
.container-lg, h1, a {
    background: transparent !important;
    border: none !important;
    box-shadow: none !important;
    padding: 0 !important;
    margin: 0 !important;
    max-width: none !important;
    width: 100% !important;
    height: 100vh !important;
    position: relative !important;
}
a {
    display: none;
}
@keyframes fadeOut {
    0% {
        opacity: 1;
    }
    70% {
        opacity: 1;
    }
    100% {
        opacity: 0;
    }
}

@keyframes fadeIn {
    0% {
        opacity: 0;
        transform: translate(-50%, -50%) scale(0.8);
    }
    100% {
        opacity: 1;
        transform: translate(-50%, -50%) scale(1);
    }
}

@keyframes emojiPop {
    0% {
        opacity: 0;
        transform: translate(-50%, -50%) scale(0.3) rotate(-10deg);
    }
    50% {
        opacity: 1;
        transform: translate(-50%, -50%) scale(1.3) rotate(5deg);
    }
    70% {
        transform: translate(-50%, -50%) scale(0.9) rotate(-2deg);
    }
    85% {
        transform: translate(-50%, -50%) scale(1.1) rotate(1deg);
    }
    100% {
        opacity: 1;
        transform: translate(-50%, -50%) scale(1) rotate(0deg);
        animation: emojiWiggle 2s ease-in-out 0.5s infinite;
    }
}

@keyframes emojiWiggle {
    0%, 100% {
        transform: translate(-50%, -50%) rotate(0deg) scale(1);
    }
    25% {
        transform: translate(-50%, -50%) rotate(-3deg) scale(1.05);
    }
    75% {
        transform: translate(-50%, -50%) rotate(3deg) scale(1.05);
    }
}

@media (max-width: 768px) {
    .question-text {
        font-size: 2.5rem;
    }
    .answer-text {
        font-size: 5rem;
    }
    .emoji-text {
        font-size: 3rem;
    }
}

@media (max-width: 480px) {
    .question-text {
        font-size: 1.8rem;
    }
    .answer-text {
        font-size: 3.5rem;
    }
    .emoji-text {
        font-size: 2.5rem;
    }
}
</style>

<script>
// Ensure the animation works properly when the page loads
document.addEventListener('DOMContentLoaded', function() {
    const question = document.getElementById('question');
    const answer = document.getElementById('answer');
    const emoji = document.getElementById('emoji');
    
    // Reset animations if page is refreshed
    question.style.animation = 'none';
    answer.style.animation = 'none';
    emoji.style.animation = 'none';
    
    // Trigger animations with a small delay
    setTimeout(() => {
        question.style.animation = 'fadeOut 5s ease-in-out forwards';
        answer.style.animation = 'fadeIn 2s ease-in-out 4s forwards';
        emoji.style.animation = 'emojiPop 1.5s ease-out 6.5s forwards';
        
        // Add continuous wiggle after the pop animation
        setTimeout(() => {
            emoji.style.animation += ', emojiWiggle 2s ease-in-out 0.5s infinite';
        }, 8000); // 6.5s delay + 1.5s pop duration
    }, 100);
});
</script>
