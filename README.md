
# Email checking tool

This open-source toolkit is designed to empower developers with the ability to verify the legitimacy of email addresses by inspecting DMARC, SPF, and DKIM records. Whether you're building an email service, implementing security measures, or simply want to ensure the authenticity of incoming emails, this tool provides a comprehensive solution.




## Key Features

DMARC Analyzer: Evaluate DMARC (Domain-based Message Authentication, Reporting, and Conformance) policies to determine the level of email authentication and protection against phishing.

SPF Checker: Verify Sender Policy Framework (SPF) records to confirm if the sending mail server is authorized to send on behalf of the domain, reducing the risk of email spoofing.

DKIM Inspector: Examine DomainKeys Identified Mail (DKIM) signatures to ensure that emails haven't been tampered with in transit and that they genuinely originate from the specified domain.

MX Record Lookup: Retrieve and analyze Mail Exchange (MX) records to validate the mail server's configuration and existence for a given domain.

Syntax Checker: Verify the syntax of email addresses to catch common mistakes and ensure adherence to RFC standards.
## USAGE

#### Importing it in your project

```http
  import (
	"fmt"
	"github.com/aaayushh7/email-verifierTool"
)

```
#### Getting started with the tool

```http
  func main() {
    email := "test@example.com"
    
    result, err := email-verifierTool.checkDomain(email)
    
    if err != nil {
        fmt.Println("Error:", err)
        return
    }

    // Add more details as needed
}
```




## Contributing

Contributions are welcome! 
If you have ideas for improvement, new features, or bug fixes, feel free to open an issue or submit a pull request.

Please adhere to this project's `code of conduct`.

