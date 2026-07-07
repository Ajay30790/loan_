
### 🔗 Links
- [GitHub Repository](https://github.com/yourusername/loan-rejection-prediction)
- [IIT Jammu Website](https://www.iitjammu.ac.in)
- [LinkedIn](https://linkedin.com)

### 📧 Contact
- **Email**: internship@iitjammu.ac.in
- **GitHub**: [github.com/yourusername](https://github.com/yourusername)
- **LinkedIn**: [linkedin.com/in/yourusername](https://linkedin.com/in/yourusername)
""")

st.markdown("---")

# GitHub and LinkedIn buttons
col1, col2, col3 = st.columns([1, 1, 1])
with col2:
    st.markdown("""
    <div style="display: flex; justify-content: center; gap: 20px; padding: 10px;">
        <a href="https://github.com" target="_blank" style="text-decoration: none;">
            <button style="background: #24292e; color: white; border: none; padding: 10px 25px; border-radius: 5px; font-weight: bold; cursor: pointer;">
                🐙 View on GitHub
            </button>
        </a>
        <a href="https://linkedin.com" target="_blank" style="text-decoration: none;">
            <button style="background: #0a66c2; color: white; border: none; padding: 10px 25px; border-radius: 5px; font-weight: bold; cursor: pointer;">
                🔗 Connect on LinkedIn
            </button>
        </a>
    </div>
    """, unsafe_allow_html=True)

st.markdown("""
<div style="text-align: center; padding: 1rem; margin-top: 2rem; border-top: 1px solid #ddd; color: #666; font-size: 0.9rem;">
    <p>🏛️ Made with ❤️ at IIT Jammu | Week 5 Assignment</p>
    <p style="font-size: 0.8rem;">© 2024 IIT Jammu - Internship Program</p>
</div>
""", unsafe_allow_html=True)

# ============================================================================
# FOOTER
# ============================================================================
st.markdown("""
<div class="footer">
<p>
    🏛️ IIT Jammu - Internship Program | Week 5 Assignment | Loan Rejection Prediction
    <br>
    <a href="https://github.com" target="_blank">GitHub</a> • 
    <a href="https://linkedin.com" target="_blank">LinkedIn</a> • 
    <a href="https://www.iitjammu.ac.in" target="_blank">IIT Jammu</a>
    <br>
    <span style="font-size: 0.8rem;">Made with ❤️ at IIT Jammu</span>
</p>
</div>
""", unsafe_allow_html=True)
