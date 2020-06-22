Change to your directory 
metadata_file = pd.read_excel('C:\Users\Hello\Desktop\metric_stream\v0.022\metadata_pipeline\metadata_documents\metadata_library.xlsx')

Change to where your contract file is 
contract_path = 'C:\Users\Hello\Desktop\metric_stream\v0.022\metadata_pipeline\data\'

Change to where you want to export the data file to 
df_metadata_match.to_csv('metadata_match0615.csv')