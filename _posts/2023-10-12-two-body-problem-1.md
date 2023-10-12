---
layout: post
title: "Dynamics bootcamp: basics of the two-body problem"
tags: ["Bootcamp", "Research", "Dynamics"]
published: true
---


Using Newton's Universal Law of Gravitation and Newton's 3rd Law of Motion, we know that, the mutual
gravitational interaction between two bodies can be expressed as the two following equations of motion (EoM):

\begin{align}
  \ddot{\mathbf{r}}_1 = -\frac{Gm_1m_2}{|\mathbf{r}_2-\mathbf{r}_1|^3}(\mathbf{r}_2-\mathbf{r}_1)~,\;\;\text{and}
  \;\;\;
  \ddot{\mathbf{r}}_2 = \frac{Gm_1m_2}{|\mathbf{r}_2-\mathbf{r}_1|^3}(\mathbf{r}_2-\mathbf{r}_1)
\end{align}

Now you must define two new variables $$({\bf r}_1,{\bf r}_2)\rightarrow({\bf r},{\bf R})$$
where

\begin{align}
{\bf r}\equiv{\bf r}_2-{\bf r}_1,\;\;\text{and}
\;\;\;
{\bf R}\equiv \frac{m_1{\bf r}_1+m_2{\bf r}_2}{m_1+m_2}
\end{align}

1. Derive the EoM for $${\bf r}$$ and $${\bf R}$$ (i.e., obtain expressions for $$\ddot{\bf r}$$ and $$\ddot{\bf R}$$)

2. Show that, in barycentric coordinates (i.e., $${\bf R}=0$$), the total angular momentum $$m_1{\bf r}_1\times\dot{\bf r}_1+m_2{\bf r}_2\times\dot{\bf r}_2$$ is equal to $$\mu{\bf r}\times\dot{\bf r}$$ where $$\mu=m_1m_2/(m_1+m_2)$$ is the system's reduced mass.

3. Show that the following two vectors are constant of motion
\begin{align}
{\bf h}\equiv {\bf r}\times\dot{\bf r}
\;\;\;\text{and}
\;\;\;
{\bf e}\equiv
\frac{1}{G(m_1+m_2)}\dot{\bf r}\times({\bf r}\times\dot{\bf r})-\frac{\bf r}{|\bf r|}
\end{align}

5. What happens if there is an additional external force $${\bf f}_{\rm ext} $$ acting on the system, namely
\begin{align}
\ddot{\bf r}={\bf f}_0 + {\bf f}_{\rm ext}
\end{align}

where $${\bf f}_0$$ is the force (per unit mass) acting on the system when only mutual gravity is accounted for. Derive expressions for $$\dot{\bf h}$$ and $$\dot{\bf e}$$.

