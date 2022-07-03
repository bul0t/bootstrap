# Accordion
https://getbootstrap.com/docs/5.2/components/accordion/

Пример кода:

    <div class="accordion" id="chapters">
        <div class="accordion-item">
            <h2 class="accordion-header" id="heading-1">
                <button class="accordion-button" type="button"
                    data-bs-toggle="collapse"
                    data-bs-target="#chapter-1">
                    Frontend
                </button>
            </h2>
            <div id="chapter-1" class="accordion-collapse collapse show"
                data-bs-parent="#chapters">
                <div class="accordion-body">
                    <p class="mb-0">HTML, CSS, JavaScript, jQuery, Bootstrap</p>
                </div>
            </div>
        </div>
        <div class="accordion-item">
            <h2 class="accordion-header" id="heading-2">
                <button class="accordion-button" type="button"
                    data-bs-toggle="collapse"
                    data-bs-target="#chapter-2">
                    Backend
                </button>
            </h2>
            <div id="chapter-2" class="accordion-collapse collapse"
                data-bs-parent="#chapters">
                <div class="accordion-body">
                    <p class="mb-0">PHP, MySQL, Bitrix Framework</p>
                </div>
            </div>
        </div>
        <div class="accordion-item">
            <h2 class="accordion-header" id="heading-3">
                <button class="accordion-button" type="button"
                    data-bs-toggle="collapse"
                    data-bs-target="#chapter-3">
                    Soft skill
                </button>
            </h2>
            <div id="chapter-3" class="accordion-collapse collapse"
                data-bs-parent="#chapters">
                <div class="accordion-body">
                    <p class="mb-0">Photoshop, Figma, Git, SEO</p>
                </div>
            </div>
        </div>
    </div>
