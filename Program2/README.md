# Add Department Field Using Git Branch, Merge, and Push

## 1. Create and switch to a new branch
```
git checkout -b update-form
```

## 2. Modify the HTML file  
Open **index.html** and add one new field:

**Department:** (add another input line below Phone)

---

## 3. Stage and commit the change
```
git add index.html
git commit -m "Add Department field to registration form"
```

---

## 4. Switch back to main branch

```
git checkout main
```

---

## 5. Merge the new branch into main
```
git merge update-form
```

---

## 6. Push updated main to GitHub
```
git push origin main
```
