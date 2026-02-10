fetch("addons.json")
  .then(res => res.json())
  .then(addons => {
    const container = document.getElementById("addons");

    addons.forEach(addon => {
      const div = document.createElement("div");
      div.className = "card";

      div.innerHTML = `
        <img src="${addon.imagem}">
        <h2>${addon.nome}</h2>
        <p>${addon.descricao}</p>
        <a href="${addon.link}" target="_blank">Ver</a>
      `;

      container.appendChild(div);
    });
  });
