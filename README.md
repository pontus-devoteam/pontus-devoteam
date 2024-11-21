```
{
  Version: "2024-10-14",
  Statement: [
      {
          Effect: "Allow",
          Principal: {
              Federated: "cognito-identity.devoteam.com",
          },
          Action: "sts:AssumeRole:AWS-Specialist:*",
      },
  ],
}
```
