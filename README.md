# Analysing-Phishing-Mail-sample
# What is Phishing?
Phishing refers to a form of cyber attack designed to deceive individuals into sharing sensitive information, including usernames, passwords, credit card details, or other personal data. Perpetrators frequently masquerade as reputable organizations or reliable entities.

# Objective
Analysis of Phishing Mail Sample
# Step 2: Collect Data
collect_data "Phishing Email Samples" {
    source "cybersecurity forums"
    source "research reports"
    source "educational websites"
    } 
# Analysis framework
 "Phishing Email Analysis" {
    include "Sender Email Address"
    include "Greeting Style"
    include "Urgency Language"
    include "Links and Attachments"
    include "Spelling and Grammar"
    include "Personal Info Requests"
    include "Branding Quality"
}
# Step 4: Analyze Emails
for each email in collected_data {
    analyze_email email {
        check_sender(email)
        check_greeting(email)
        check_urgency(email)
        check_links(email)
        check_grammar(email)
        check_personal_requests(email)
        check_branding(email)
    }
}
        The tool which was used is "MX Toolbox" which is free and open source tool can be 
        used to perform header analysis and identify the phishing mails etc.
# Step 5: Generate Characteristics Report
generate_report "Common Characteristics" {
    output "Sender Email Address"
    output "Greeting Style"
    output "Urgency Language"
    output "Links and Attachments"
    output "Spelling and Grammar"
    output "Personal Info Requests"
    output "Branding Quality"
}

The Result and Header analysis report was attached.
