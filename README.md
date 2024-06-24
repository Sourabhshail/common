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


    const getStatus = (status: string | undefined) => {
    if (status === '0') {
      return 'Lead Created';
    } else if (status === '1') {
      return 'Application Filing Started';
    } else if (status === '2') {
      return 'Application Filed';
    } else if (status === '3') {
      return 'Appraisal In Progress';
    } else if (status === '4') {
      return 'Sanctioned';
    } else if (status === '5') {
      return 'Application Rejected';
    }
  };
  
  const getColor = (status: string | undefined) => {
    if (status === '0') {
      return '#ffcd3d';
    } else if (status === '1') {
      return '#d88b5d';
    } else if (status === '2') {
      return '#6f8661';
    } else if (status === '3') {
      return '#ffcd3d';
    } else if (status === '4') {
      return '#d88b5d';
    } else if (status === '5') {
      return '#6f8661';
    }
  };
