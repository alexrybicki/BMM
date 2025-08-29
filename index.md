
<div id="question" class="question-text">Is the BMM in development?</div>
<div id="answer" class="answer-text">NO</div>

<style>
body {
    margin: 0;
    padding: 0;
    background-color: #15161cde;
    color: #fff;
    font-family: 'Arial', sans-serif;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    overflow: hidden;
}

.question-text {
    font-size: 4rem;
    font-weight: bold;
    text-align: center;
    opacity: 1;
    animation: fadeOut 5s ease-in-out forwards;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    white-space: nowrap;
}

.answer-text {
    font-size: 8rem;
    font-weight: bold;
    text-align: center;
    color: #ff4444;
    opacity: 0;
    animation: fadeIn 2s ease-in-out 4s forwards;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    text-shadow: 3px 3px 6px rgba(255, 68, 68, 0.5);
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

@media (max-width: 768px) {
    .question-text {
        font-size: 2.5rem;
    }
    .answer-text {
        font-size: 5rem;
    }
}

@media (max-width: 480px) {
    .question-text {
        font-size: 1.8rem;
    }
    .answer-text {
        font-size: 3.5rem;
    }
}
</style>

<script>
// Ensure the animation works properly when the page loads
document.addEventListener('DOMContentLoaded', function() {
    const question = document.getElementById('question');
    const answer = document.getElementById('answer');
    
    // Reset animations if page is refreshed
    question.style.animation = 'none';
    answer.style.animation = 'none';
    
    // Trigger animations with a small delay
    setTimeout(() => {
        question.style.animation = 'fadeOut 5s ease-in-out forwards';
        answer.style.animation = 'fadeIn 2s ease-in-out 4s forwards';
    }, 100);
});
</script>
