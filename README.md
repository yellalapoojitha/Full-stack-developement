function navigate(page) {
    window.location.hash = page;
    renderPage();
}

window.addEventListener(
    "hashchange",
    renderPage
);# Full-stack-developement
