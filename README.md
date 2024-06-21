# common
 encryptedValue = {
            password: `${Math.random().toString(36).slice(2, 8)}${data.salt2}${hash}${data.salt1}${Math.random().toString(36).slice(2, 8)}`, 
            key: data.key}
