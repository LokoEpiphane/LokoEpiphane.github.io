## 📖 **Table of Contents**
- [🔗 About Me](#about-me)
- [🏆 Awards](#awards)
- [📚 Research Publications](#research-publications)
- [🎤 Academic Talks](#academic-presentations-and-talks)
- [👨‍🏫 Teaching Experience](#teaching-experience)
- [📄 CV](#cv)

---

## <a name="about-me"></a> ℹ️ About Me  

### **PhD Candidate in Control, Stability, and Stabilization Theory**  

I am currently pursuing a PhD under the joint supervision of **[Antoine Chaillet](https://l2s.centralesupelec.fr/u/chaillet-antoine/)** (L2S, CentraleSupélec, Paris-Saclay University) and **[Amaury Hayat](http://cermics.enpc.fr/~hayata/)** (CERMICS, École des Ponts), since September 2022.  

My research focuses on control theory, especially the stability and stabilization of finite and infinite-dimensional systems, including time-delay systems and partial differential equations (PDEs).  

---

<div id="content-container">

### 🏆 <a name="awards"></a> Awards  
<div class="content-section">
- **September 2024**: *Best Presentation Award of the Automatic team at L2S*, PhD Student Day  
- **September 2021 - July 2022**: *Bezout M2 scholarship*  
</div>

---

### 📚 <a name="research-publications"></a> Research Publications  
<div class="content-section">
### **Journal Articles**  
1. **[A. Hayat and E. Loko](http://cermics.enpc.fr/~hayata/F_equivalence_general_linear.pdf)**, *Rapid Stabilization of General Linear Systems with F-equivalence*, **Preprint, 2024**.  
2. **[E. Loko, A. Chaillet, and I. Karafyllis](https://onlinelibrary.wiley.com/doi/full/10.1002/rnc.7229)**, *Building Coercive Lyapunov–Krasovskii Functionals Based on Razumikhin and Halanay Approaches*, **International Journal of Robust and Nonlinear Control, 2024**.  
</div>

---

### 🎤 <a name="academic-presentations-and-talks"></a> Academic Presentations and Talks  
<div class="content-section">
- **Growth Condition to Ensure Input-to-State Stability of Time-Delay Systems with Point-Wise Dissipation**  
  *IEEE Conference on Decision and Control, December 2024*  
</div>

---

### 👨‍🏫 <a name="teaching-experience"></a> Teaching Experience  
<div class="content-section">
- **September 2024 - January 2025**  
  *Analysis and Partial Differential Equations*, **1st-year undergraduate students (30 hours)**  
</div>

---

### 📄 <a name="cv"></a> CV  
<div class="content-section">
📄 **[Download my CV](https://github.com/user-attachments/files/18690641/CV_Epiphane.pdf)**  
</div>

</div>

---

### 🔎 **Navigation**  
[⬆️ Back to Top](#about-me)  

---

## 📜 **Custom JavaScript and CSS**

<style>
/* Cache toutes les sections sauf "About Me" */
.content-section {
    display: none;
}

/* Style des liens pour la navigation */
#table-of-contents a {
    text-decoration: none;
    color: #0077cc;
    font-weight: bold;
    cursor: pointer;
}

#table-of-contents a:hover {
    text-decoration: underline;
}
</style>

<script>
document.addEventListener("DOMContentLoaded", function() {
    // Récupérer tous les liens du sommaire
    let links = document.querySelectorAll("#table-of-contents a");

    links.forEach(link => {
        link.addEventListener("click", function(event) {
            event.preventDefault(); // Empêche le scroll par défaut

            // Masquer toutes les sections
            document.querySelectorAll(".content-section").forEach(section => {
                section.style.display = "none";
            });

            // Récupérer l'ID de la section à afficher
            let sectionId = this.getAttribute("href").substring(1);
            let sectionToShow = document.querySelector(`[name="${sectionId}"]`).nextElementSibling;

            // Afficher la section correspondante
            if (sectionToShow) {
                sectionToShow.style.display = "block";
            }
        });
    });
});
</script>

