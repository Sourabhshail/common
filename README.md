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
