/* Shared site script: mobile menu, scroll reveal, rotating roles */
document.documentElement.classList.add('js');

document.addEventListener('DOMContentLoaded', function () {

    /* Mobile menu */
    var toggle = document.querySelector('.nav-toggle');
    var links = document.querySelector('.nav-links');
    if (toggle && links) {
        toggle.addEventListener('click', function () {
            links.classList.toggle('open');
        });
    }

    /* Scroll reveal */
    var items = document.querySelectorAll('.reveal');
    if ('IntersectionObserver' in window) {
        var io = new IntersectionObserver(function (entries) {
            entries.forEach(function (e) {
                if (e.isIntersecting) {
                    e.target.classList.add('in');
                    io.unobserve(e.target);
                }
            });
        }, { threshold: 0.12 });
        items.forEach(function (el) { io.observe(el); });
    } else {
        items.forEach(function (el) { el.classList.add('in'); });
    }

    /* Typing role line (home page only) */
    var target = document.getElementById('typed-role');
    if (target) {
        var roles = ['Cybersecurity Student', 'IT Support Specialist', 'Aspiring SOC Analyst', 'Lifelong Learner'];
        var r = 0, c = 0, deleting = false;
        (function tick() {
            var word = roles[r];
            target.textContent = word.substring(0, c);
            if (!deleting && c < word.length) { c++; setTimeout(tick, 80); }
            else if (!deleting) { deleting = true; setTimeout(tick, 1600); }
            else if (c > 0) { c--; setTimeout(tick, 40); }
            else { deleting = false; r = (r + 1) % roles.length; setTimeout(tick, 300); }
        })();
    }
});