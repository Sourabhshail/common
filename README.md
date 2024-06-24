let lead = {
                  ...leadInfo,
                  ...values,
                  parentId: partner.id,
                  bankStatement: values.bankStatementLocal ? 'Y' : 'N',
                  gstRegime: values.gstRegimeLocal ? 'Y' : 'N',
                  itrFiling: values.itrFilingLocal ? 'Y' : 'N',
                  // dateOfIncorp: Moment(values.dateOfIncorp).format('YYYY-MM-DD'),
                };

https://apiuat.sidbi.in/connect-app/api/partners/0/leads





 entityName?: string;
  pan?: string;
  loanAmount?: number;
  loanType?: string;
  customerType?: string;
  itrFilingLocal?: boolean;
  bankStatementLocal?: boolean;
  gstRegimeLocal?: boolean;
  itrFiling?: string;
  bankStatement?: string;
  gstRegime?: string;
  mobileNo?: string;
  emailId?: string;
  officeAddress?: string;
  city?: string;
  state?: string;
  pincode?: number;
  // dateOfIncorp?: string;
  applicationFillingBy?: string;
  branchName?: string;
  customerConcent?: string;
  otp?: string;
  dateCreated?: string;
  leadStatus?: string;
  
  
