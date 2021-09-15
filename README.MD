#Instructions


1. Edit "Extract Invoice data Dispatcher" variables "PathForFiles" and "QueueName" - point to correct path where invoices are present and correct queue name.
2. Run Dispatcher process to generate transactions.
3. Run Performer process to consume transactions.
4. Extracted data is saved to directory "Data\Data.xlsx".
5. You can also check out Tests directory for both Performer and Dispatcher to see how they've been tested.