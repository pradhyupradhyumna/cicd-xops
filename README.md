# CI/CD Deployment to EC2 via GitHub Actions

This project demonstrates a complete CI/CD pipeline that automatically deploys a simple web application to an AWS EC2 instance using GitHub Actions.

---

## Project Structure
cicd-webapp/
├── index.html
├── README.md
├── .github/
│ └── workflows/
│ └── deploy.yml
└── Screenshots/
├── Webpage_from_EC2.png
└── GitHub_Actions_Success.png

---

## Files

- `index.html`: The main web page.
- `README.md`: Project documentation.
- `.github/workflows/deploy.yml`: GitHub Actions workflow file.
- `Screenshots/`: Contains screenshots of the deployed web page and pipeline result.

---

## GitHub Secrets Used

- `EC2_PUBLIC_IP`
- `SSH_USERNAME`
- `SSH_PRIVATE_KEY`

---

## Screenshots

### Deployed Web Page

![Web Output](Screenshots/Webpage_from_EC2.png)

### GitHub Actions Workflow Success

![CI/CD Pipeline](Screenshots/GitHub_Actions_Success.png)
