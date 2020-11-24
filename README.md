# Bug-MaterialLibTextInputLayoutAutoScrollingIssue

How to reproduce:
1. Run the code, copy paste a very long text into the TextInputEditText field.
2. Try to click on the first few lines.
3. Observe the scrolling behavior.
4. Upgrade the version of material lib to implementation 'com.google.android.material:material:1.2.1'
5. Repeat step 1-3.
6. Observation: With 1.2.1, the TextInputEditText always auto scroll to the bottom of the TextInputEditText after cursor changes.

Solution:
- Downgrade the version of material lib to implementation 'com.google.android.material:material:1.1.0'
