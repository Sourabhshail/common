# common
 request: { 
    partnerId: number | undefined,
    entityName: string | undefined,
    pan: string | undefined,
    loanAmount: number | undefined,
    emailId: string | undefined,
    mobileNo: string | undefined
  }


 return fetch(`${apiEndpoint}/api/partners/${request.partnerId}/sendConsent`, {
      method: "POST",
      headers: {
        "Authorization": `Bearer ${token}`,
        "Content-Type": "application/json",
      },
