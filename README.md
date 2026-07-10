<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Secure AI Assistant for Financial Services Lab</title>

<style>
body {
    font-family: Arial, Helvetica, sans-serif;
    max-width: 1000px;
    margin: auto;
    padding: 20px;
    line-height: 1.6;
}

h1, h2, h3 {
    color: #232F3E;
}

section {
    margin-bottom: 40px;
}

code {
    background: #f4f4f4;
    padding: 2px 4px;
}

pre {
    background: #f4f4f4;
    padding: 12px;
    overflow-x: auto;
    border-left: 4px solid #ff9900;
}

table {
    border-collapse: collapse;
    width: 100%;
}

th, td {
    border: 1px solid #ccc;
    padding: 8px;
}

th {
    background: #efefef;
}
</style>
</head>

<body>

<header>
<h1>Secure AI Assistant for Financial Services Lab</h1>
<p><strong>Services:</strong> Amazon Bedrock, Amazon S3, IAM, CloudTrail, CloudWatch</p>
</header>

<section id="overview">
<h2>Overview</h2>
<p>Financial institutions are increasingly adopting generative AI to improve employee productivity, automate document analysis, and assist with fraud investigations. However, these AI systems introduce new security risks, including unauthorized access to sensitive financial information, prompt injection attacks, accidental data leakage, and insufficient auditing.</p>
</section>

<section id="objectives">
<h2>Objective</h2>
In this lab, you will assume the role of a Cloud Security Engineer for a fictional financial institution, SecureBank, that is deploying an internal AI assistant powered by Amazon Bedrock. The assistant enables financial analysts to query internal documents, customer transaction summaries, fraud reports, and company policies.

Your responsibility is to secure the AI assistant by implementing proper access controls, protecting confidential information, monitoring AI activity, and enabling governance through logging and auditing.
</section>

<section id="part1">
<h2>Part 1 – Create the Secure S3 Bucket</h2>

<h3>Step 1</h3>
<ol>
<li>Open the AWS Console.</li>
<li>Navigate to Amazon S3.</li>
<li>Create a bucket named <code>bank-ai-assistant-lab</code>.</li>
<li>Leave Block Public Access enabled.</li>
<li>Enable Bucket Versioning.</li>
<li>Create the bucket.</li>
</ol>
<h3>Step 2</h3>
<a href="downloads/Secure-Bank-Datasets.zip" download>
    📥 Download Lab Dataset
</a> 

<ol>
    <li>Create folders</li>
</ol>
</section>

<!-- Remaining sections -->

</body>
</html>
