# Document-Formatting-Script-for-Headings-in-DOCX-Files
This Python script utilizes the docx library to process a DOCX file, specifically targeting paragraphs that resemble chapter headings and numbered patterns. The script employs regular expressions to identify different patterns in the text, such as chapters and numbered sections. 

Install the python-docx Library:
Make sure you have the python-docx library installed. If you haven't installed it yet, you can use the following command:

bash
Copy code
pip install python-docx
Create a New Python Script:
Open your preferred text editor or integrated development environment (IDE) and create a new Python script. Copy and paste the provided script into your new file.

Adjust Input and Output Paths:
Modify the input_file_path and output_file_path variables in the script to point to your actual input and desired output file paths.

python
Copy code
input_file_path = 'path/to/your/input.docx'
output_file_path = 'path/to/your/output.docx'
Run the Script:
Save your script and run it using the Python interpreter:

bash
Copy code
python script.py
Replace script.py with the name you gave to your Python script file.

Check the Output:
After running the script, check the specified output file path (output_file_path) for the modified document. The headings in the output document should now have different font sizes based on the patterns identified by the script.

Adjustments (if needed):
If the script doesn't produce the desired results or if your document structure differs, you may need to adjust the regular expressions or the formatting logic in the process_paragraph and replace_with_formatted_run functions. Review the patterns and formatting options to suit your specific requirements.
