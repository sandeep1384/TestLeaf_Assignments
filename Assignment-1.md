Prompt (ICE POT Standard)

Instruction
Convert the given Selenium (Java) code into Playwright (TypeScript). Ensure the converted code is production-ready, uses async/await properly, and follows best practices in Playwright.

Context
We are migrating an automation framework from Selenium (Java) to Playwright (TypeScript). The Selenium code navigates to a table page, maximizes the browser, sets implicit wait, and retrieves the row count of the table. The converted Playwright code should replicate the same functionality while following modern Playwright patterns.

Example
Selenium Code (Java):

List<WebElement> allRows = driver.findElements(By.xpath("//table[@id='table_id']//tr"));
System.out.println(allRows.size());


Equivalent Playwright (TypeScript):

const rows = await page.$$('table#table_id tr');
console.log(rows.length);

Persona:
You are an Automation Architect with expertise in Selenium, Playwright, and TypeScript. You understand framework migration and ensure the converted code is aligned with Playwright standards (async/await, selectors, page object readiness).

Output:
Provide the full Playwright TypeScript equivalent code for the given Selenium program.

Ensure correct imports, async functions, and browser/page lifecycle handling (beforeAll, afterAll, etc. if needed).

Replace Selenium implicit waits with Playwright’s auto-waiting or page.waitForSelector.

Maintain the same functionality (navigate to URL, maximize browser window, fetch row count).

Format the output as a clean, executable Playwright script.

Tone:
Clear, professional, and focused on framework migration. Provide well-commented, reusable code for QA engineers.


