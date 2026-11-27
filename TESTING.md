
# Student Management System – Testing Checklist

## 1. Application Functionality
- [ ] Application starts successfully.
- [ ] Add student function works.
- [ ] View students function works.
- [ ] Search student function works.
- [ ] Update student function works.
- [ ] Delete student function works.
- [ ] Invalid inputs are handled correctly.

## 2. Database Testing
- [ ] SQLite database is created successfully.
- [ ] Student records are saved correctly.
- [ ] Student records remain after restarting.
- [ ] No unwanted duplicate records are created.

## 3. Infrastructure as Code (IaC)
- [ ] Python environment is checked.
- [ ] Required dependencies are installed.
- [ ] Required folders are created automatically.
- [ ] Configuration files are created.
- [ ] Database is initialised automatically.
- [ ] Application starts automatically.

## 4. Idempotency and Error Handling
- [ ] First execution of setup.py is successful.
- [ ] Second execution of setup.py is successful.
- [ ] Existing student records are preserved.
- [ ] No unnecessary duplicate files are created.
- [ ] Errors are handled correctly.

## 5. Final Project Verification
- [ ] All required files are included.
- [ ] README instructions are accurate.
- [ ] IaC explanation matches the script.
- [ ] All four members have contributed.
- [ ] Final testing is completed.
- [ ] Repository is ready for submission.
