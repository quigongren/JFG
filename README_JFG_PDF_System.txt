JFG PDF Generator System (v1)

Place in your JFG GitHub repo like:

JFG/
  scripts/
    jfg_pdf_generator.py
  docs/
    templates/
      JFG_Sample_Report.json
      JFG_PDF_Template.txt
  exports/
    README_exports.txt

Setup:

1. Install dependency:

   pip install reportlab

2. Generate a sample report:

   python scripts/jfg_pdf_generator.py \
       --input docs/templates/JFG_Sample_Report.json \
       --output exports/JFG_Sample_Report.pdf
