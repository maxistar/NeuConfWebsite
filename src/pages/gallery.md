---
layout: ../layouts/MarkdownLayout.astro
title: Галерея
---

<section class="gallery">
  <img src="/gallery/BC_0030.jpg" alt="Andrew Buchman's speeh 1" onclick="openDialog(this.src)" />
  <img src="/gallery/BC_0047.jpg" alt="Andrew Buchman's speeh 2" onclick="openDialog(this.src)" />
  <img src="/gallery/BC_0033.jpg" alt="Andrew Buchman's speeh 3" onclick="openDialog(this.src)" />
  <img src="/gallery/BC_0010.jpg" alt="Andrew Buchman's speeh 4" onclick="openDialog(this.src)" />
  <img src="/gallery/BC_0063.jpg" alt="Maxim Starikov's speech" onclick="openDialog(this.src)" />
  <img src="/gallery/BC_0013.jpg" alt="Alexander Sazonov's speech 1" onclick="openDialog(this.src)" />
  <img src="/gallery/BC_0055.jpg" alt="Alexander Sazonov's speech 2" onclick="openDialog(this.src)" />
  <img src="/gallery/BC_0051.jpg" alt="Alexander Sazonov's speech 3" onclick="openDialog(this.src)" />
  <img src="/gallery/BC_0022.jpg" alt="Vas3k's speech 1" onclick="openDialog(this.src)" />
  <img src="/gallery/BC_0025.jpg" alt="Vas3k's speech 2" onclick="openDialog(this.src)" />
  <img src="/gallery/BC_0052.jpg" alt="Group photo couch" onclick="openDialog(this.src)" />
  <img src="/gallery/BC_0016.jpg" alt="Group photo chairs" onclick="openDialog(this.src)" />
  <img src="/gallery/BC_0019.jpg" alt="Group photo bright" onclick="openDialog(this.src)" />
  <img src="/gallery/BC_0060.jpg" alt="Group photo fun" onclick="openDialog(this.src)" />
  <img src="/gallery/BC_0067.jpg" alt="Group photo" onclick="openDialog(this.src)" />
</section>

<div id="imgModal" class="modal" onclick="closeDialog()">
  <span class="close">&times;</span>
  <img class="modal-content" id="modalImage" />
</div>

<script>
    function openDialog(src) {
        const modal = document.getElementById("imgModal");
        const modalImg = document.getElementById("modalImage");
        modal.style.display = "block";
        modalImg.src = src;
}

    function closeDialog() {
        document.getElementById("imgModal").style.display = "none";
    }
</script>



[**Купить билет**](/tickets/)
