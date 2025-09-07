---
title: ""
linkTitle: "Grille d'évaluation"
type: docs
weight: 19
cascade:
  type: docs
---

{{< raw-html >}}

<style>
    .evaluation-content {
        font-family: Arial, sans-serif;
        line-height: 1.4;
        font-size: 12px;
        max-width: 1200px;
        margin: 0 auto;
    }
    
    .evaluation-content table {
        width: 100%;
        border-collapse: collapse;
        margin-bottom: 20px;
        box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    
    .evaluation-content th, .evaluation-content td {
        border: 1px solid #333;
        padding: 8px;
        text-align: left;
        vertical-align: top;
    }
    
    .level-header {
        background-color: #E6F3FF;
        font-weight: bold;
        text-align: center;
        width: 50px;
    }
    
    .points-header {
        background-color: #B3D9FF;
        font-weight: bold;
        text-align: center;
        width: 60px;
    }
    
    .column-header {
        background-color: #B3D9FF;
        font-weight: bold;
        text-align: center;
        font-size: 13px;
    }
    
    .content-cell {
        font-size: 11px;
    }
    
    .highlight {
        background-color: #FFFFCC;
    }
    
    .contexte {
        color: #8E24AA;
        font-weight: bold;
    }
    
    .sens {
        color: #D32F2F;
        font-weight: bold;
    }
    
    .strategie {
        color: #1976D2;
        font-weight: bold;
    }
    
    .competence {
        color: #388E3C;
        font-weight: bold;
    }
    
    .evaluation {
        color: #F57C00;
        font-weight: bold;
    }
    
    .page-title {
        font-size: 18px;
        font-weight: bold;
        text-align: center;
        margin-bottom: 30px;
        color: #2B5AA0;
        padding: 15px;
        background-color: #f8f9fa;
        border-radius: 8px;
    }
    
    .analysis-box {
        background-color: #F5F5F5;
        padding: 20px;
        margin-top: 30px;
        border-radius: 8px;
        border-left: 4px solid #2B5AA0;
    }
    
    .competence-grid {
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        gap: 15px;
        margin-top: 15px;
    }
    
    .competence-card {
        background: white;
        padding: 15px;
        border-radius: 8px;
        border: 2px solid;
        box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }
    
    .contexte-card { border-color: #8E24AA; }
    .sens-card { border-color: #D32F2F; }
    .strategie-card { border-color: #1976D2; }
    
    .conversion-grid {
        display: grid;
        grid-template-columns: 1fr 1fr;
        gap: 20px;
        margin-top: 15px;
    }
    
    .conversion-card {
        background: white;
        padding: 15px;
        border-radius: 8px;
        border: 1px solid #ddd;
        box-shadow: 0 1px 3px rgba(0,0,0,0.1);
    }
    
    .note-box {
        background-color: #FFF3E0;
        padding: 15px;
        border-radius: 8px;
        margin-top: 15px;
        border-left: 4px solid #FF9800;
    }
    
    @media (max-width: 768px) {
        .competence-grid, .conversion-grid {
            grid-template-columns: 1fr;
        }
        
        .evaluation-content {
            font-size: 11px;
        }
        
        .evaluation-content table {
            font-size: 10px;
        }
    }
</style>

<div class="evaluation-content">
    <div class="page-title">
        GRILLE POUR L'ÉVALUATION DE LA COMPRÉHENSION DE L'ÉCRIT ET DE L'ORAL<br>
        <small>Attestation de niveau de compétence </small>
    </div>

    <table>
        <thead>
            <tr>
                <th rowspan="2" class="level-header">Niveau</th>
                <th class="column-header">Identification du contexte ou de la situation d'énonciation</th>
                <th class="points-header">Points score</th>
                <th class="column-header">Identification des réseaux de sens</th>
                <th class="points-header">Points score</th>
                <th class="column-header">Identification des stratégies de communication</th>
                <th class="points-header">Points score</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td class="level-header">C2</td>
                <td class="content-cell highlight">
                    <span class="contexte">Peut comprendre sans difficulté à de rares exceptions près les éléments relatifs au contexte et à la situation d'énonciation</span>
                </td>
                <td class="points-header">30</td>
                <td class="content-cell highlight">
                    <span class="sens">Peut comprendre sans difficulté, à de rares exceptions près, les réseaux de sens</span>
                </td>
                <td class="points-header">30</td>
                <td class="content-cell highlight">
                    <span class="strategie">Peut comprendre sans difficulté, à de rares exceptions près, les stratégies de communication</span>
                </td>
                <td class="points-header">30</td>
            </tr>
            <tr>
                <td class="level-header">C1</td>
                <td class="content-cell highlight">
                    <span class="contexte">Peut identifier les détails fins ou l'implicite tout en les replaçant dans le contexte.</span>
                </td>
                <td class="points-header">20</td>
                <td class="content-cell highlight">
                    <span class="sens">Peut identifier et analyser la logique interne d'un document ou dossier en distinguant le cas échéant ce qui est de l'ordre de la digression.</span>
                </td>
                <td class="points-header">20</td>
                <td class="content-cell highlight">
                    <span class="strategie">Peut identifier l'articulation de documents.<br>
                    Peut identifier la tonalité d'un propos : ironie, humour, stratégies interpersonnelles, etc.</span>
                </td>
                <td class="points-header">20</td>
            </tr>
            <tr>
                <td class="level-header">B2</td>
                <td class="content-cell highlight">
                    <span class="contexte">Peut identifier la richesse d'un contexte ou d'une situation d'énonciation, y compris en relevant le cas échéant des éléments implicites.</span>
                </td>
                <td class="points-header">10</td>
                <td class="content-cell highlight">
                    <span class="sens">Peut identifier la cohérence globale d'un document ou dossier : identifier les principales raisons pour ou contre une idée ; reconstituer une chronologie d'événements dans un récit ; repérer des ruptures chronologiques, etc.</span>
                </td>
                <td class="points-header">10</td>
                <td class="content-cell highlight">
                    <span class="strategie">Peut repérer une intention en distinguant l'expression d'un point de vue de l'exposé de faits.<br>
                    Peut identifier des éléments implicites qui sous-tendent l'articulation des documents entre eux.</span>
                </td>
                <td class="points-header">10</td>
            </tr>
            <tr>
                <td class="level-header">B1</td>
                <td class="content-cell highlight">
                    <span class="contexte">Peut relever des informations détaillées sur le contexte (objet, enjeux, perspective narrative, expériences relatées, etc.) et établir des liens entre elles.</span>
                </td>
                <td class="points-header">5</td>
                <td class="content-cell highlight">
                    <span class="sens">Peut relever l'essentiel des éléments porteurs de sens d'un document ou dossier : reconstituer le plan général d'un texte ; identifier des liens de causalité simples, etc.</span>
                </td>
                <td class="points-header">5</td>
                <td class="content-cell highlight">
                    <span class="strategie">Peut identifier l'expression de points de vue, souhaits et/ou perspectives.<br>
                    Peut identifier la nature de l'articulation entre les documents (lien chronologique, illustratif, d'opposition, etc.)</span>
                </td>
                <td class="points-header">5</td>
            </tr>
            <tr>
                <td class="level-header">A2</td>
                <td class="content-cell">
                    <span class="contexte">Peut relever des informations explicites sur le contexte (thème, lieux, personnes, événements, etc.).</span>
                </td>
                <td class="points-header">3</td>
                <td class="content-cell">
                    <span class="sens">Peut comprendre globalement un document ou dossier : identifier le sujet principal, regrouper des termes d'un même champ lexical.</span>
                </td>
                <td class="points-header">3</td>
                <td class="content-cell">
                    <span class="strategie">Peut identifier la nature du (ou des) documents et la mettre en lien avec quelques éléments du contenu.</span>
                </td>
                <td class="points-header">3</td>
            </tr>
            <tr>
                <td class="level-header">A1</td>
                <td class="content-cell">
                    <span class="contexte">Peut relever des informations isolées simples et les articuler en partie les unes aux autres.</span>
                </td>
                <td class="points-header">1</td>
                <td class="content-cell">
                    <span class="sens">Peut construire une amorce de compréhension en relevant des mots ou expressions.</span>
                </td>
                <td class="points-header">1</td>
                <td class="content-cell">
                    <span class="strategie">Peut relever quelques données ou caractéristiques évidentes d'un document (dates, titres, paragraphes, etc.)</span>
                </td>
                <td class="points-header">1</td>
            </tr>
        </tbody>
    </table>

    <div class="analysis-box">
        <h3 style="color: #2B5AA0; margin-top: 0;">Les trois piliers de l'évaluation CECRL en compréhension</h3>
        
        <div class="competence-grid">
            <div class="competence-card contexte-card">
                <h5 style="margin-top: 0; color: #8E24AA;">🔍 Situation d'énonciation</h5>
                <p style="font-size: 11px; margin: 5px 0;"><strong>A1-A2 :</strong> Informations explicites et factuelles</p>
                <p style="font-size: 11px; margin: 5px 0;"><strong>B1-B2 :</strong> Contexte enrichi, éléments implicites</p>
                <p style="font-size: 11px; margin: 5px 0;"><strong>C1-C2 :</strong> Détails fins, analyse contextuelle complexe</p>
            </div>
            <div class="competence-card sens-card">
                <h5 style="margin-top: 0; color: #D32F2F;">🧠 Réseaux de sens</h5>
                <p style="font-size: 11px; margin: 5px 0;"><strong>A1-A2 :</strong> Compréhension globale, champs lexicaux</p>
                <p style="font-size: 11px; margin: 5px 0;"><strong>B1-B2 :</strong> Cohérence, causalités, chronologies</p>
                <p style="font-size: 11px; margin: 5px 0;"><strong>C1-C2 :</strong> Logique interne, digressions identifiées</p>
            </div>
            <div class="competence-card strategie-card">
                <h5 style="margin-top: 0; color: #1976D2;">💬 Stratégies de communication</h5>
                <p style="font-size: 11px; margin: 5px 0;"><strong>A1-A2 :</strong> Nature des documents, liens évidents</p>
                <p style="font-size: 11px; margin: 5px 0;"><strong>B1-B2 :</strong> Points de vue, intentions, articulations</p>
                <p style="font-size: 11px; margin: 5px 0;"><strong>C1-C2 :</strong> Tonalités, ironie, stratégies sophistiquées</p>
            </div>
        </div>

        </div>
    </div>

    <div class="analysis-box" style="margin-top: 30px;">
        <h3 style="color: #2B5AA0; margin-top: 0;">📊 Tableaux de conversion - Compréhension </h3>
        
        <div class="conversion-grid">
            <div class="conversion-card">
                <h4 class="evaluation">🎓 PREMIÈRE</h4>
                <p style="font-size: 11px; margin: 10px 0; font-weight: bold;"> Objectif B1/B2 :</p>
                <ul style="font-size: 10px; margin: 5px 0;">
                    <li><strong>A1 :</strong> 1-8 points score → Notes 1-7/20</li>
                    <li><strong>A2 :</strong> 8-13 points score → Notes 8-12/20</li>
                    <li><strong>B1 :</strong> 13-20+ points score → Notes 13-20/20</li>
                </ul>
            </div>
            <div class="conversion-card">
                <h4 class="evaluation">🎓 TERMINALE</h4>
                <p style="font-size: 11px; margin: 10px 0; font-weight: bold;"> Objectif B2 :</p>
                <ul style="font-size: 10px; margin: 5px 0;">
                    <li><strong>A1 :</strong> 1-5 points score → Notes 1-4/20</li>
                    <li><strong>A2 :</strong> 6-14 points score → Notes 5-10/20</li>
                    <li><strong>B1 :</strong> 15-30 points score → Notes 11-19/20</li>
                    <li><strong>B2+ :</strong> 30+ points score → Notes 20/20</li>
                </ul>
            </div>
        </div>

    </div>
</div>

{{< /raw-html >}}
